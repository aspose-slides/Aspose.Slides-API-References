---
title: get_ZoomImage()
second_title: Aspose.Slides pro C++ – reference API
description: Získá obrázek pro zoom objekt. Přečtěte si IPPImage.
type: docs
weight: 79
url: /cs/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() metoda


Získá obrázek pro zoom objekt. Přečtěte si [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Poznámky


Příklad ukazuje změnu obrázku Zoom objektu: 
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
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)