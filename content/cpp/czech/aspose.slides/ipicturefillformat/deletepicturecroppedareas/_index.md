---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides pro C++ referenci API
description: Odstraní oříznuté oblasti výplně obrázku.
type: docs
weight: 430
url: /cs/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() metoda

Odstraňuje oříznuté oblasti výplně [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### Návratová hodnota

Oříznutý obrázek nebo původní obrázek, pokud oříznutí není nutné.
## Poznámky

Tato metoda převádí metafily WMF/EMF na rastrový PNG obrázek při ořezávání.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Získá PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Smaže oříznuté oblasti obrázku PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPPImage](../../ippimage/)
* Třída [IPictureFillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)