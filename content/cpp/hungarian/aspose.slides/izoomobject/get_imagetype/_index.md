---
title: get_ImageType()
second_title: Aspose.Slides C++ API referenciája
description: "A zoom objektum képtípusát adja vissza. Olvassa el ZoomImageType. Alapértelmezett érték: Preview"
type: docs
weight: 1
url: /hu/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() metódus

Lekéri a zoom objektum képtípusát. Olvasd el [ZoomImageType](../../zoomimagetype/). Alapértelmezett érték: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Megjegyzések

Megadja, hogy a Zoom objektum a diá előnézetet vagy egy borítóképet használja-e.

Ez a példa bemutatja az Image Type értékének Preview-ra változtatását. Ebben az esetben a Zoom objektum aktuális képe a dia képére változik: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Lásd még

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)