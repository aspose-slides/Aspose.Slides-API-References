---
title: get_ZoomImage()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene l'immagine per l'oggetto zoom. Leggi IPPImage.
type: docs
weight: 79
url: /it/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() metodo

Ottiene l'immagine per l'oggetto zoom. Leggi [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Osservazioni

L'esempio dimostra come modificare l'immagine di un oggetto Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)