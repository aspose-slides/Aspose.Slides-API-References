---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides för C++ API-referens
description: Ta bort beskurna områden i fyllningen Picture.
type: docs
weight: 430
url: /sv/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() metod


Ta bort beskurna områden i fyllningen [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### Returvärde

Beskuren bild eller originalbild om beskärning inte är nödvändig.
## Anmärkningar


Denna metod konverterar WMF/EMF metafiler till raster PNG bild medan den beskär.



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
* Class [IPPImage](../../ippimage/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)