---
title: GetImage()
second_title: Référence API Aspose.Slides pour C++
description: "Renvoie la vignette de la forme. Le type des limites de la vignette de forme ShapeThumbnailBounds::Shape est utilisé par défaut."
type: docs
weight: 651
url: /fr/aspose.slides/shape/getimage/
---
## Shape::GetImage() méthode

Renvoie la vignette de la forme. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) le type des limites de la vignette de forme est utilisé par défaut.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### Valeur de retour

[Shape](../) vignette.

## Shape::GetImage(ShapeThumbnailBounds, float, float) méthode

Renvoie la vignette de la forme.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) le type des limites de la vignette. |
| scaleX | **float** | Échelle X |
| scaleY | **float** | Échelle Y |

### Valeur de retour

[Shape](../) la vignette ou null dans le cas où [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) est utilisé et qu'une forme n'a pas d'éléments visibles.

## Voir aussi

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)