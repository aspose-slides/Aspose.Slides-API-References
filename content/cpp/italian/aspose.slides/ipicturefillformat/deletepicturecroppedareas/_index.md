---
title: DeletePictureCroppedAreas()
second_title: Riferimento API di Aspose.Slides per C++
description: Elimina le aree ritagliate del riempimento Picture.
type: docs
weight: 430
url: /it/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() metodo

Elimina le aree ritagliate del riempimento [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### Valore restituito

Immagine ritagliata o immagine originale se il ritaglio non è necessario.

## Osservazioni

Questo metodo converte i metafili WMF/EMF in immagine PNG raster durante il ritaglio.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Elimina le aree ritagliate dell'immagine PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [IPictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)