---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides för C++ API-referens
description: Ta bort beskurna områden i fyllningsbilden Picture.
type: docs
weight: 430
url: /sv/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() method


Ta bort beskurna områden i fyllningen [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### Returvärde

Beskuren bild eller originalbild om beskärning inte är nödvändig.
## Anmärkningar


Denna metod konverterar WMF/EMF-metafiler till raster-PNG-bild samtidigt som den beskär.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Hämtar PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Tar bort beskurna områden i PictureFrame-bilden
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPPImage](../../ippimage/)
* Klass [IPictureFillFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)