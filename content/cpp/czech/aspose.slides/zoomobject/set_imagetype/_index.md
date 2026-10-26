---
title: set_ImageType()
second_title: "Aspose.Slides pro C++ – reference API"
description: "Nastaví typ obrázku zoom objektu. Zapište ZoomImageType. Výchozí hodnota: Preview"
type: docs
weight: 14
url: /cs/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) metoda

Nastaví typ obrázku objektu ZoomObject. Zapište [ZoomImageType](../../zoomimagetype/). Výchozí hodnota: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Poznámky

Určuje, zda objekt Zoom používá náhled snímku nebo obrázek obálky.

Další příklad ukazuje změnu Image Type na hodnotu Preview. V tomto případě se aktuální obrázek objektu Zoom změní na obrázek snímku:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Viz také

* Enum [ZoomImageType](../../zoomimagetype/)
* třída [ZoomObject](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)