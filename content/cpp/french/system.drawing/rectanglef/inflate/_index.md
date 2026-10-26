---
title: Inflate()
second_title: Référence de l'API Aspose.Slides pour C++
description: Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en conservant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les quantités spécifiées.
type: docs
weight: 261
url: /fr/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) méthode

Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en conservant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les quantités spécifiées.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| width | **float** | La quantité par laquelle la width du rectangle doit être augmentée dans les deux directions |
| height | **float** | La quantité par laquelle la height du rectangle doit être augmentée dans les deux directions |

## RectangleF::Inflate(const SizeF\&) méthode

Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en conservant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les quantités spécifiées par les valeurs width et height de l'objet taille spécifié de manière correspondante.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | L'objet [SizeF](../../sizef/) spécifiant les quantités d'augmentation de la width et de la height du rectangle |

## RectangleF::Inflate(const RectangleF\&, float, float) méthode

Augmente la largeur et la hauteur du rectangle représenté par l'objet spécifié, tout en conservant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les quantités spécifiées.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Un rectangle à gonfler |
| x | **float** | La quantité par laquelle la width du rectangle doit être augmentée dans les deux directions |
| y | **float** | La quantité par laquelle la height du rectangle doit être augmentée dans les deux directions |

### Valeur de retour

L'objet [RectangleF](../) représentant le rectangle agrandi

## Voir aussi

* Classe [RectangleF](../)
* Classe [SizeF](../../sizef/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)