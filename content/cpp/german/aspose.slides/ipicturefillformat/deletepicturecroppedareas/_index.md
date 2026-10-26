---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides für C++ API-Referenz
description: Löschen Sie die beschnittenen Bereiche der Füllung Picture.
type: docs
weight: 430
url: /de/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() Methode

Löschen Sie beschnittene Bereiche der Füllung [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### Rückgabewert

Beschnittener Bild oder Originalbild, wenn kein Beschnitt erforderlich ist.

## Anmerkungen

Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild, während sie zuschneidet.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ruft das PictureFrame ab
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Löscht beschnittene Bereiche des PictureFrame-Bildes
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [IPictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)