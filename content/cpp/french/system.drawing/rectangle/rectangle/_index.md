---
title: Rectangle()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance de l'objet Rectangle qui représente un rectangle dont les coordonnées X et Y ainsi que les valeurs de largeur et de hauteur sont fixées à 0.
type: docs
weight: 1
url: /fr/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() constructeur

Construit une nouvelle instance de l’objet [Rectangle](../) qui représente un rectangle dont les coordonnées X et Y ainsi que les valeurs de largeur et de hauteur sont réglées à 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) constructeur

Construit une nouvelle instance de l’objet [Rectangle](../) qui représente un rectangle avec les coordonnées spécifiées de son coin supérieur gauche ainsi que sa largeur et sa hauteur.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | Une valeur de la coordonnée X du coin supérieur gauche du rectangle |
| y | int | Une valeur de la coordonnée Y du coin supérieur gauche du rectangle |
| width | int | La largeur du rectangle |
| height | int | La hauteur du rectangle |

## Rectangle::Rectangle(const Point\&, const Size\&) constructeur

Construit une nouvelle instance de l’objet [Rectangle](../) qui représente un rectangle dont les coordonnées du coin supérieur gauche sont spécifiées comme une instance de la classe [Point](../../point/) et dont la largeur et la hauteur sont spécifiées comme une instance de la classe [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Spécifie l’emplacement du coin supérieur gauche du rectangle |
| size | const [Size](../../size/)\& | Spécifie la largeur et la hauteur du rectangle |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) constructeur

Construit une nouvelle instance de l’objet [Rectangle](../) qui représente le rectangle équivalent à celui spécifié.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Une instance de la classe **System::Windows::Forms::Screen::Rectangle_** qui spécifie la position et la taille du rectangle à représenter par l’objet en cours de construction |

## Voir aussi

* Classe [Rectangle](../)
* Classe [Point](../../point/)
* Classe [Size](../../size/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)