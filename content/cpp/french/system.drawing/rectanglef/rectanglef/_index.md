---
title: RectangleF()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance de l'objet RectangleF qui représente un rectangle dont les coordonnées X et Y ainsi que les valeurs de largeur et de hauteur sont définies à 0.
type: docs
weight: 1
url: /fr/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() constructeur

Construit une nouvelle instance de l'objet [RectangleF](../) qui représente un rectangle dont les coordonnées X et Y ainsi que les valeurs de largeur et de hauteur sont définies à 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) constructeur

Construit une nouvelle instance de l'objet [RectangleF](../) qui représente un rectangle avec les coordonnées spécifiées de son coin supérieur gauche ainsi que sa largeur et sa hauteur.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | Une valeur de la coordonnée X du coin supérieur gauche du rectangle |
| y | **float** | Une valeur de la coordonnée Y du coin supérieur gauche du rectangle |
| width | **float** | La largeur du rectangle |
| height | **float** | La hauteur du rectangle |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) constructeur

Construit une nouvelle instance de l'objet [RectangleF](../) qui représente un rectangle dont les coordonnées de son coin supérieur gauche sont spécifiées comme une instance de la classe [PointF](../../pointf/) et sa largeur et sa hauteur comme une instance de la classe [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Spécifie l'emplacement du coin supérieur gauche du rectangle |
| size | const [SizeF](../../sizef/)\& | Spécifie la largeur et la hauteur du rectangle |

## RectangleF::RectangleF(const Rectangle\&) constructeur

Construit une nouvelle instance de l'objet [RectangleF](../) qui représente le rectangle équivalent à celui spécifié.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Une instance de la classe [Rectangle](../../rectangle/) qui spécifie la position et la taille du rectangle à représenter par l'objet en cours de construction |

## Voir aussi

* Classe [RectangleF](../)
* Classe [PointF](../../pointf/)
* Classe [SizeF](../../sizef/)
* Classe [Rectangle](../../rectangle/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)