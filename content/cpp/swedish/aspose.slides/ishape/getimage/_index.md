---
title: GetImage()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar formens miniatyrbild. ShapeThumbnailBounds::Shape typ av miniatyrbildsgränser används som standard."
type: docs
weight: 547
url: /sv/aspose.slides/ishape/getimage/
---
## IShape::GetImage() metod


Returnerar formens miniatyrbild. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) typen för formens miniatyrbildsgränser används som standard.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### Returvärde

[Shape](../../shape/) miniatyrbild.

## IShape::GetImage(ShapeThumbnailBounds, float, float) metod


Returnerar formens miniatyrbild.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) typ av miniatyrbildsgränser. |
| scaleX | **float** | X-skala |
| scaleY | **float** | Y-skala |

### Returvärde

[Shape](../../shape/) miniatyrbild eller null om [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) används och en form inte har synliga element.

## Se även

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)