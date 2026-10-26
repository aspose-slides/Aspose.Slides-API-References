---
title: set_ImageType()
second_title: Aspose.Slides C++ API referencia
description: "Beállítja egy zoom objektum képtípusát. Írja ZoomImageType. Alapértelmezett érték: Preview"
type: docs
weight: 14
url: /hu/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) metódus


Beállítja egy zoom objektum képtípusát. Írja [ZoomImageType](../../zoomimagetype/). Alapértelmezett érték: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Megjegyzés


Megadja, hogy a Zoom objektum a dia előnézetet vagy egy borítóképet használ-e. 

A következő példa bemutatja az Image Type előzetes értékre való módosítását. Ebben az esetben egy Zoom objektum aktuális képe a dia képére változik: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Lásd még

* Enum [ZoomImageType](../../zoomimagetype/)
* Osztály [ZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)