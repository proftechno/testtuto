# testtuto

## Etape 1
Faire glisser le bloc quand bouton A pressé
sur votre espace de travail.

```blocks
input.onButtonPressed(Button.A, function () {
	
})
```
## Etape 2
Faire glisser dans le bloc précédent
le bloc "montrer symbôle" et sélectionner
le symbôle croix

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.No)
})
```

## Etape 3
Rajouter un bloc pause (ms) et changer
la valeur pour avoir 5s.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.No)
    basic.pause(5000)
})
```

## Etape finale
Et enfin ajouter à la suite le bloc
effacer l'écran, puis utiliser le simulateur
pour visualiser le programme sur la carte.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.No)
    basic.pause(5000)
    basic.clearScreen()
})
```
