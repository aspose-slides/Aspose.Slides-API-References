---
title: GetImage()
second_title: Aspose.Slides voor C++ API Referentie
description: "Retourneert de miniatuur van de vorm. ShapeThumbnailBounds::Shape miniatuurgrens-type wordt standaard gebruikt."
type: docs
weight: 651
url: /nl/aspose.slides/shape/getimage/
---
## Shape::GetImage() methode


Retourneert de miniatuur van de vorm. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type wordt standaard gebruikt.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### Retourwaarde

[Shape](../) miniatuur.

## Shape::GetImage(ShapeThumbnailBounds, float, float) methode


Retourneert de miniatuur van de vorm.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) thumbnail bounds type. |
| scaleX | **float** | X-schaal |
| scaleY | **float** | Y-schaal |

### Retourwaarde

[Shape](../) miniatuur of null in het geval dat [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) wordt gebruikt en een vorm geen zichtbare elementen heeft.

## Zie ook

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [Shape](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)