---
title: get_ImageType()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Získá typ obrázku objektu zoom. Přečtěte si ZoomImageType. Výchozí hodnota: Preview"
type: docs
weight: 1
url: /cs/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() metoda

Získá typ obrázku objektu zoom. Přečtěte si [ZoomImageType](../../zoomimagetype/). Výchozí hodnota: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Poznámky

Určuje, zda objekt Zoom používá náhled snímku nebo úvodní obrázek. 

Následující příklad ukazuje změnu Image Type na hodnotu Preview. V tomto případě se aktuální obrázek objektu Zoom změní na obrázek snímku: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Viz také

* Enum [ZoomImageType](../../zoomimagetype/)
* Třída [ZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)