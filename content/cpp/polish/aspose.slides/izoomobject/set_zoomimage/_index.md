---
title: set_ZoomImage()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Ustawia obraz dla obiektu Zoom. Zapisz IPPImage.
type: docs
weight: 92
url: /pl/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) metoda


Ustawia obraz dla obiektu Zoom. Zapisz [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## Uwagi


Przykład pokazuje zmianę obrazu obiektu Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPPImage](../../ippimage/)
* Klasa [IZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)