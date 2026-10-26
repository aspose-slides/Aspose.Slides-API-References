---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides für C++ API-Referenz
description: Löscht beschnittene Bereiche der Fill Picture.
type: docs
weight: 430
url: /de/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() Methode

Löscht die beschnittenen Bereiche der Füllung [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### Rückgabewert

Beschnittenes Bild oder Originalbild, wenn kein Beschneiden erforderlich ist.

## Anmerkungen

Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild während des Beschneidens.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Holt das PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Löscht beschnittene Bereiche des PictureFrame-Bildes
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [PictureFillFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)