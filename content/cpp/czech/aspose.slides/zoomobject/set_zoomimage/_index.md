---
title: set_ZoomImage()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví obrázek pro zoom objekt. Zapište IPPImage.
type: docs
weight: 92
url: /cs/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) metoda

Nastaví obrázek pro zoom objekt. Zapište [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## Poznámky

Příklad demonstruje změnu obrázku Zoom objektu:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPPImage](../../ippimage/)
* Třída [ZoomObject](../)
* Obor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)