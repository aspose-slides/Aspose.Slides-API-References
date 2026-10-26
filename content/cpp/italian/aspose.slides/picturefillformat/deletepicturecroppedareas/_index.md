---
title: DeletePictureCroppedAreas()
second_title: Riferimento API Aspose.Slides per C++
description: Elimina le aree ritagliate del riempimento Picture.
type: docs
weight: 430
url: /it/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() method

Elimina le aree ritagliate del riempimento [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### Valore di ritorno

Immagine ritagliata o immagine originale se il ritaglio non è necessario.

## Osservazioni

Questo metodo converte i metafile WMF/EMF in immagini raster PNG durante il ritaglio.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Elimina le aree ritagliate dell'immagine del PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPPImage](../../ippimage/)
* Classe [PictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)