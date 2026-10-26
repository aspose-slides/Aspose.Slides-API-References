---
title: get_ZoomImage()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene l'immagine per l'oggetto Zoom. Leggi IPPImage.
type: docs
weight: 79
url: /it/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() metodo

Ottiene l'immagine per l'oggetto Zoom. Leggi [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Osservazioni

L'esempio dimostra come cambiare l'immagine di un oggetto Zoom:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [ZoomObject](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)