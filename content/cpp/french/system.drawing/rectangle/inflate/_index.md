---
title: Inflate()
second_title: Référence de l'API Aspose.Slides pour C++
description: Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en conservant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les quantités spécifiées.
type: docs
weight: 261
url: /fr/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) method

Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en conservant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les quantités spécifiées.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La quantité par laquelle la largeur du rectangle doit être augmentée dans les deux directions |
| height | int | La quantité par laquelle la hauteur du rectangle doit être augmentée dans les deux directions |

## Rectangle::Inflate(const Size\&) method

Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en conservant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les quantités spécifiées par les valeurs de largeur et de hauteur de l'objet size spécifié, respectivement.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| size | const [Size](../../size/)\& | L'objet [Size](../../size/) spécifiant les quantités d'augmentation de la largeur et de la hauteur du rectangle |

## Rectangle::Inflate(const Rectangle\&, int, int) method

Augmente la largeur et la hauteur du rectangle représenté par l'objet spécifié, tout en conservant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les quantités spécifiées.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Un rectangle à agrandir |
| x | int | La quantité par laquelle la largeur du rectangle doit être augmentée dans les deux directions |
| y | int | La quantité par laquelle la hauteur du rectangle doit être augmentée dans les deux directions |

### Valeur de retour

L'objet [Rectangle](../) représentant le rectangle agrandi

## Voir aussi

* Classe [Rectangle](../)
* Classe [Size](../../size/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)