# ML

Work we've done so far.
Task left to do: 

#8 : Ce n’est pas le nombre de valeurs manquantes mais le nombre de valeurs non NA
#16 : Approfondir l’analyse : decroissance jusqu’à la crise des subprimes ou il est redevnu dur, puis reprise de la decroissance jusqu’à la période actuelle, augmentation des taux car nécessité de freiner l’inflation qui impact les taux d’emprunts + Titre a changer
#19 : On enleve les taux croates etc .. car on suppose qu’apporte plus de bruits que d’info interessante (données parasites)
# 20 : Aucune valeur manquante Analyse : Faut pas juste dire ce qu'on fait, faut dire pourquoi on le fait. La ca fait juste du listing. Par exemple ici c'est afin de voir d'eventuels outliers par rapport a la moyenne. Mauvais titre
# 22 : # : On peut peut etre faire une analyse sur les pays en question qui ont exhiber le plus de variation (une initerpretation economique voire financière)
#24 : #: (Quelles explication on pourrait donner sur le rationel derriere ca) --> On voit que les morgage rates sont plutôt corrélé avec les pays puissant de l’europe (forte santé économique
#29 : Rajouter les légendes + préciser pourquoi on est obligé de saisonnaliser les données
#34 : Titre
#36 : Pas d’hypothèse de normalité pour la regression linéaire (Théorème de Cochran)
#40 : changement pour mettre des majuscules a toutes les RMSE et MSE
#46 : Analyse de la RMSE sinon ca sert a rien de le mettre dans le test , et la clairement avec notre RMSE on a des signes d'overfitting, il faut qu'on verifie les nuances entre RMSE et MSE (laquelle est meilleure et pour quelle situation)
# 47 : On est good niveau overfitting pas trop de difference entre notre erreur sur l’echantillon de test vs train (Rappel : si error_train << error_test --> overfitting par rapport aux données d’entrainement, si error_train >> error_test --> underfitting : on a encore de la marge pour apprendre de nos données , si error_train ~ error_test : good le modèle généralise bien
# 52 : Pour les titres la diff = le spread + Je sais pas trop pour l’interpretation
# 62 : Pourquoi tu rounds tes errors des fois et d’autres tu les round pas ? --> même format pour une meilleure interpretation
# 67 : Changement de random_state pour le lasso
#68 : a quoi c'est du ca ? Parce qu'un modèle de R^2 = 1 c'est clairement de l'overfitting , et il faut aussi qu'on précise au moins une fois que signifie le R2 ! Aussi il faut préciser ce que signifie chaque concept interpretation la premiere fois qu'on l'utilise

Reste a faire :

# Verification des fautes d’orthographe + verification de la formulation
# Verification des titres
#: Il faudra aussi a voir si le contenu du cours a bien été mis en relation avec la problématique
#: Voir comment verifier qu'il n'y pas de surapprentissage avec les modèles supervisés
#: Verifier pour chaque model qu'on utilise quels sont les outils qui permettent d'interpreter notre modèle parmi variable d'importance, LIME, SHAP etc ...
