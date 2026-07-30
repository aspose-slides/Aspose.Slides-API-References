---
title: get_ZoomImage()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Získá obrázek pro objekt Zoom. Přečtěte IPPImage.
type: docs
weight: 79
url: /cs/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() metoda

Získá obrázek pro objekt Zoom. Přečtěte [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Poznámky

Příklad ukazuje změnu obrázku objektu Zoom:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPPImage](../../ippimage/)
* Třída [IZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)