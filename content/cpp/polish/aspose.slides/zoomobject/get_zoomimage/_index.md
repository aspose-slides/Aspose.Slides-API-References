---
title: get_ZoomImage()
second_title: Aspose.Slides dla C++ Referencja API
description: Pobiera obraz dla obiektu zoom. Przeczytaj IPPImage.
type: docs
weight: 79
url: /pl/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() metoda


Pobiera obraz dla obiektu Zoom. Przeczytaj [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Uwagi


Przykład demonstruje zmianę obrazu obiektu Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IPPImage](../../ippimage/)
* Klasa [ZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)