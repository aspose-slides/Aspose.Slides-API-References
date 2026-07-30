---
title: set_ZoomImage()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví obrázek pro objekt zoom. Zapište IPPImage.
type: docs
weight: 92
url: /cs/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) metoda


Nastaví obrázek pro objekt zoom. Zapište [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
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
* třída [IPPImage](../../ippimage/)
* třída [IZoomObject](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)