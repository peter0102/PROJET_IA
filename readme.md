# Stratégie d'évaluation  
Pour évaluer le plateau, on parcourt la grille et on compte les paires et triplés de jetons alignés en ligne, en colonne et en diagonale.  
On ajoute au score final des points en fonction du nombre de jetons alignées dans tous les sens du joueur concerné, et on en retire pour les jetons alignés du joueur adverse.  
Une priorité est mise sur la défense en retirant plus de points lorsque l’adversaire à des jetons alignés. Ainsi on essaye de s’assurer que l’IA ne puisse pas perdre.  
