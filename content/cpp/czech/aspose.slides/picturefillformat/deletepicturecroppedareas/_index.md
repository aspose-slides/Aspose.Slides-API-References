---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Odstraní oříznuté oblasti výplně Picture.
type: docs
weight: 430
url: /cs/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() metoda


Odstraňte oříznuté oblasti výplně [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### Návratová hodnota

Oříznutý obrázek nebo originální obrázek, pokud ořez není nutný.
## Poznámky


Tato metoda převádí soubory WMF/EMF na rastrový PNG obrázek při ořezávání.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Odstraní oříznuté oblasti obrázku PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPPImage](../../ippimage/)
* Třída [PictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)