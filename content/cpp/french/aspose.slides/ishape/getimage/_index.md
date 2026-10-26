---
title: GetImage()
second_title: Référence API Aspose.Slides pour C++
description: "Renvoie la miniature de la forme. Le type de limites de la miniature ShapeThumbnailBounds::Shape est utilisé par défaut."
type: docs
weight: 547
url: /fr/aspose.slides/ishape/getimage/
---
## IShape::GetImage() méthode

Renvoie la miniature de la forme. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) le type de limites de la miniature de la forme est utilisé par défaut.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### Valeur de retour

[Shape](../../shape/) miniature.

## IShape::GetImage(ShapeThumbnailBounds, float, float) méthode

Renvoie la miniature de la forme.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) type de limites de la miniature. |
| scaleX | **float** | échelle X |
| scaleY | **float** | échelle Y |

### Valeur de retour

[Shape](../../shape/) miniature ou nul dans le cas où [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) est utilisé et qu'une forme n'a pas d'éléments visibles.

## Voir aussi

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [IShape](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)