---
title: GetImage()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert een vormminiatuur. ShapeThumbnailBounds::Shape vormminiatuur begrenzingstype wordt standaard gebruikt."
type: docs
weight: 547
url: /nl/aspose.slides/ishape/getimage/
---
## IShape::GetImage() methode


Retourneert een miniatuur van de vorm. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) vorm miniatuur begrenzingstype wordt standaard gebruikt.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### Retourwaarde

[Shape](../../shape/) miniatuur.

## IShape::GetImage(ShapeThumbnailBounds, float, float) methode


Retourneert een miniatuur van de vorm.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) miniatuurbegrenzingstype. |
| scaleX | **float** | X-schaal |
| scaleY | **float** | Y-schaal |

### Retourwaarde

[Shape](../../shape/) miniatuur of null in het geval dat [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) wordt gebruikt en een vorm geen zichtbare elementen heeft.

## Zie ook

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)