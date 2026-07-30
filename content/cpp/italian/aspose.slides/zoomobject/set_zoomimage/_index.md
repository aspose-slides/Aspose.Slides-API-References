---
title: set_ZoomImage()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta l'immagine per l'oggetto zoom. Scrivi IPPImage.
type: docs
weight: 92
url: /it/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) metodo

Imposta l'immagine per l'oggetto Zoom. Scrivi [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## Osservazioni

L'esempio dimostra come cambiare un'immagine di un oggetto Zoom:
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
* Libreria [Aspose.Slides](../../../)