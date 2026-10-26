---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides C++ API Referencia
description: A kitöltés Picture levágott területeinek törlése.
type: docs
weight: 430
url: /hu/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() metódus


Törli a kitöltés levágott területeit [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### Visszatérési érték

Levágott kép vagy eredeti kép, ha a vágás nem szükséges.
## Megjegyzések


Ez a metódus WMF/EMF meta fájlokat raster PNG képpé konvertál vágás közben.



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
* Osztály [PictureFillFormat](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)