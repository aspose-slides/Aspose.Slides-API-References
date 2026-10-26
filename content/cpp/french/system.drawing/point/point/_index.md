---
title: Point()
second_title: Référence API Aspose.Slides pour C++
description: Construit un nouvel objet Point et initialise les valeurs de ses coordonnées X et Y à 0.
type: docs
weight: 1
url: /fr/system.drawing/point/point/
---
## Point::Point() constructeur


Construit un nouvel objet [Point](../) et initialise les valeurs de ses coordonnées X et Y à 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) constructeur


Construit un nouvel objet [Point](../) et l'initialise avec les valeurs spécifiées.

```cpp
System::Drawing::Point::Point(int x, int y)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La valeur de la coordonnée X |
| y | int | La valeur de la coordonnée Y |

## Point::Point(const Size\&) constructeur


Construit un nouvel objet [Point](../) et initialise les valeurs de ses coordonnées X et Y avec les valeurs de largeur et de hauteur de l'objet [SizeF](../../sizef/) spécifié, respectivement.

```cpp
System::Drawing::Point::Point(const Size &size)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Un objet [SizeF](../../sizef/) dont les valeurs de largeur et de hauteur sont utilisées pour initialiser les valeurs des coordonnées X et Y de l'objet [Point](../) en cours de création |

## Point::Point(int) constructeur


Construit un nouvel objet [Point](../) et initialise la valeur de la coordonnée X avec la valeur formée par les 16 bits de poids fort du entier 32 bits spécifié, et la valeur de la coordonnée Y avec la valeur formée par les 16 bits de poids faible du même entier 32 bits.

```cpp
System::Drawing::Point::Point(int dw)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dw | int | La valeur entière 32 bits dont les 16 bits de poids fort spécifient la valeur de la coordonnée X et les 16 bits de poids faible spécifient la valeur de la coordonnée Y de l'objet en cours de création |

## Voir aussi

* Classe [Point](../)
* Classe [Size](../../size/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)