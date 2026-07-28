---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides dla C++ – Referencja API
description: Usuwa przycięte obszary wypełnienia obrazu.
type: docs
weight: 430
url: /pl/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() metoda

Usuń przycięte obszary wypełnienia [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### Wartość zwracana

Przycięty obraz lub oryginalny obraz, jeśli przycinanie nie jest konieczne.
## Uwagi

Ta metoda konwertuje pliki metafile WMF/EMF na rastrowy obraz PNG podczas przycinania.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Usuwa przycięte obszary obrazu PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPPImage](../../ippimage/)
* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)