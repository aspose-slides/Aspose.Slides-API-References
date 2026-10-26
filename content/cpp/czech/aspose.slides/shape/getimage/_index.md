---
title: GetImage()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací miniaturu tvaru. Typ ohraničení miniatury tvaru ShapeThumbnailBounds::Shape se použije jako výchozí."
type: docs
weight: 651
url: /cs/aspose.slides/shape/getimage/
---
## Shape::GetImage() metoda


Vrací miniaturu tvaru. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type se použije jako výchozí.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### Návratová hodnota

[Shape](../) miniaturu.

## Shape::GetImage(ShapeThumbnailBounds, float, float) metoda


Vrací miniaturu tvaru.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) thumbnail bounds type. |
| scaleX | **float** | škála X |
| scaleY | **float** | škála Y |

### Návratová hodnota

[Shape](../) miniatura nebo null v případě, že [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) se použije a tvar nemá viditelné prvky.

## Viz také

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImage](../../iimage/)
* Třída [Shape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)