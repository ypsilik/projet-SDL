
Projet : 
modeliser un protocole (type hdlc) avec un num de sequence
il doit prendre en compte les erreurs et défauts : paquets qui arrive pas, qui est incomplet, message perdu...


- ETAPE 1 : faire modele ou tout ce passe bien a 3 etats : on envoie, transmission et renvoi acquittement a la fin quand tout se passe bien
on envoie msg 1, on recoit ack 1 ....
- ETAPE 2 : on add un pb : un paquet es tpas recu ==> mise en place timer avat redemande / renvoia => nv scénario
- ETAPE 3 : on add un pb ...
- des qu'un pb arrive on le traite / déclanchement de retransmission

mono-directionnel, quand perte message, retransmission tt message a partir du premier message de perdu
 


SOUTENANCE : montré modele quo'n a fait, et transfert du projet avec une/deux pages explicatition sur comment le lancer, et utiliser le truc. lister les cas et opérations possibles en fonction de ce qu'uon a fait
