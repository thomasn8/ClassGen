# ClassGen
Generate c++ Class files (*.cpp and *.hpp) based on templates from ClassGen/class_files

## Copier le dossier ClassGen quelque part, par exemple dans /Users/thomas

	$ cd ~ && git clone https://github.com/thomasn8/ClassGen.git

## Dans .zshrc ou .bashrc, modifier $PATH avec le chemin vers ClassGen

	$ vim .zshrc

Ajouter cette ligne:

	PATH=$PATH:/Users/thomas/ClassGen

## Dans ce même .zshrc ou .bashrc, ajouter une alias pour ClassGen.sh

Et cette ligne:

	alias class="ClassGen.sh"

## Utiliser cette alias comme commande, depuis n'importe où, pour générer des classes dans le dossier courant

	$ class

Affichera:

#### C++ class files generator (*.hpp + *.cpp)
#### Enter ClassName(s) (separated by whitespace) :

Possibilités:
- écrire 1 ClassName et presser 'enter'
- écrire plusieurs ClassName séparé par des espaces et presser 'enter'
- quitter le prog en laissant le champ vide et en pressant 'enter' (ou ctrl-c)
