---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides C++ API referenciája
description: Törli a kitöltő kép levágott területeit.
type: docs
weight: 430
url: /hu/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() metódus


A kitöltés [Picture](../../picture/) levágott területeit törli.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### Visszatérési érték

Levágott kép vagy eredeti kép, ha a vágás nem szükséges.
## Megjegyzések


Ez a metódus WMF/EMF metafájlokat raster PNG képpé konvertál vágás közben.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Lekéri a PictureFrame-et
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Törli a PictureFrame kép levágott területeit
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPPImage](../../ippimage/)
* Osztály [IPictureFillFormat](../)
* Névterület [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)