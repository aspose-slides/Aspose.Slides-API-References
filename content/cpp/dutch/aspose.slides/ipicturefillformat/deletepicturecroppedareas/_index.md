---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijder bijgesneden gebieden van de vulling Picture.
type: docs
weight: 430
url: /nl/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() methode


Verwijder bijgesneden gedeeltes van de vulling [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### Retourwaarde

Bijgesneden afbeelding of originele afbeelding als bijsnijden niet nodig is.
## Opmerkingen


Deze methode converteert WMF/EMF-metabestanden naar raster-PNG-afbeelding tijdens het bijsnijden.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Verkrijgt het PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Verwijdert bijgesneden gebieden van de PictureFrame-afbeelding
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [IPictureFillFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)