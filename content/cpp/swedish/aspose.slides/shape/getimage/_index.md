---
title: GetImage()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar formens miniatyrbild. ShapeThumbnailBounds::Shape formens miniatyrgränstyp används som standard."
type: docs
weight: 651
url: /sv/aspose.slides/shape/getimage/
---
## Shape::GetImage() metod


Returnerar formens miniatyr. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) formens miniatyrgränstyp används som standard.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### Returvärde

[Shape](../) miniatyrbild.

## Shape::GetImage(ShapeThumbnailBounds, float, float) metod


Returnerar formens miniatyrbild.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) miniatyrgränstyp. |
| scaleX | **float** | X-skala |
| scaleY | **float** | Y-skala |

### Returvärde

[Shape](../) miniatyrbild eller null om [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) används och en form inte har synliga element.

## Se även

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IImage](../../iimage/)
* klass [Shape](../)
* namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)