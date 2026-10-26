---
title: set_ImageType()
second_title: Aspose.Slides C++ API referenciája
description: "Beállítja egy zoom objektum kép típusát. Írja ZoomImageType. Alapértelmezett érték: Preview"
type: docs
weight: 14
url: /hu/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) metódus

Beállítja a zoom objektum kép típusát. Írja [ZoomImageType](../../zoomimagetype/). Alapértelmezett érték: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Megjegyzés

Megadja, hogy a Zoom objektum a diá előnézetet vagy egy borítóképet használ-e.  

Ez a példa bemutatja a Kép Típus Preview értékre történő módosítását. Ebben az esetben a Zoom objektum aktuális képe a dia képre változik: 
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