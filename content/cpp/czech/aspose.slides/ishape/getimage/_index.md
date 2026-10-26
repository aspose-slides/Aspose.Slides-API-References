---
title: GetImage()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací miniaturu tvaru. Typ ohraničení miniatury tvaru ShapeThumbnailBounds::Shape se použije jako výchozí."
type: docs
weight: 547
url: /cs/aspose.slides/ishape/getimage/
---
## IShape::GetImage() metoda


Vrací miniaturu tvaru. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) typ ohraničení miniatury tvaru se použije jako výchozí.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### Návratová hodnota

[Shape](../../shape/) miniaturu.

## IShape::GetImage(ShapeThumbnailBounds, float, float) metoda


Vrací miniaturu tvaru.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) typ ohraničení miniatury |
| scaleX | **float** | měřítko X |
| scaleY | **float** | měřítko Y |

### Návratová hodnota

[Shape](../../shape/) miniatura nebo null v případě, že [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) je použito a tvar nemá viditelné elementy.

## Viz také

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)