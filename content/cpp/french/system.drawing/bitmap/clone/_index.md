---
title: Clone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de l'objet actuel.
type: docs
weight: 183
url: /fr/system.drawing/bitmap/clone/
---
## Bitmap::Clone() méthode


Crée une copie de l'objet actuel.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Valeur de retour

Une copie de l'objet actuel.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) méthode


Crée un objet [Bitmap](../) qui représente une copie d'une région de l'image bitmap représentée par l'objet actuel.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Le rectangle qui spécifie la région à copier |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Le format de pixel pour le nouveau [Bitmap](../) |

### Valeur de retour

L'objet [Bitmap](../) créé

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) méthode


Crée un objet [Bitmap](../) qui représente une copie d'une région de l'image bitmap représentée par l'objet actuel.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Le rectangle qui spécifie la région à copier |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Le format de pixel pour le nouveau [Bitmap](../) |

### Valeur de retour

L'objet [Bitmap](../) créé

## Voir aussi

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)