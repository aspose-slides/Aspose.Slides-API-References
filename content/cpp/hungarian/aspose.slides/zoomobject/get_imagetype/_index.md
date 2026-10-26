---
title: get_ImageType()
second_title: Aspose.Slides for C++ API Referencia
description: "Lekéri a zoom objektum képtípusát. Olvasd el a ZoomImageType-ot. Alapértelmezett érték: Preview"
type: docs
weight: 1
url: /hu/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() metódus


Lekéri a zoom objektum képtípusát. Olvasd el [ZoomImageType](../../zoomimagetype/). Alapértelmezett érték: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Megjegyzések


Megadja, hogy a Zoom objektum a dia előnézetet vagy egy borítóképet használ-e. 

A következő példa bemutatja, hogyan változtatható meg az Image Type a Preview értékre. Ebben az esetben a Zoom objektum aktuális képe a dia képre változik: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Lásd még

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)