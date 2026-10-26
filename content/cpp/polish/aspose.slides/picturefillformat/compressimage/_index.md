---
title: CompressImage()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Kompresuje obraz, zmniejszając jego rozmiar w zależności od wielkości kształtu i określonej rozdzielczości. Opcjonalnie usuwa także wycięte fragmenty.
type: docs
weight: 443
url: /pl/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) metoda

Kompresuje obraz, zmniejszając jego rozmiar w zależności od wielkości kształtu i określonej rozdzielczości. Opcjonalnie usuwa także wycięte fragmenty.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Jeśli true, metoda usunie wycięte fragmenty obrazu, co może dodatkowo zmniejszyć jego rozmiar. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Docelowa rozdzielczość dla kompresji, określona jako wartość wyliczenia [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Wartość zwracana

Wartość **bool** wskazująca, czy obraz został pomyślnie skompresowany. Zwraca ****true****

## Uwagi

Ta metoda zmienia rozmiar i rozdzielczość obrazu podobnie jak funkcja PowerPoint "Picture Format -> Compress Pictures".

jeśli obraz został zmieniony rozmiar lub przycięty, w przeciwnym razie ****false****

. 

Poniższy przykład pokazuje, jak użyć metody **CompressImage**, aby zmniejszyć rozmiar obrazu w prezentacji, ustawiając docelową rozdzielczość i usuwając wycięte fragmenty: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Skompresuj obraz z docelową rozdzielczością 150 DPI (rozdzielczość internetowa) i usuń wycięte fragmenty
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) metoda

Kompresuje obraz, zmniejszając jego rozmiar w zależności od wielkości kształtu i określonej rozdzielczości. Opcjonalnie usuwa także wycięte fragmenty.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Jeśli true, metoda usunie wycięte fragmenty obrazu, co może dodatkowo zmniejszyć jego rozmiar. |
| resolution | **float** | Docelowa rozdzielczość w DPI. Wartość ta musi być dodatnia i określa, jak obraz zostanie zmieniony rozmiarem. |

### Wartość zwracana

Wartość **bool** wskazująca, czy obraz został pomyślnie skompresowany. Zwraca ****true****

## Uwagi

Ta metoda zmienia rozmiar i rozdzielczość obrazu podobnie jak funkcja PowerPoint "Picture Format -> Compress Pictures".

jeśli obraz został zmieniony rozmiar lub przycięty, w przeciwnym razie ****false****

. 

Poniższy przykład pokazuje, jak użyć metody **CompressImage**, aby zmniejszyć rozmiar obrazu w prezentacji, ustawiając docelową rozdzielczość i usuwając wycięte fragmenty: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Skompresuj obraz z docelową rozdzielczością 150 DPI (rozdzielczość internetowa) i usuń wycięte fragmenty
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Rozdzielczość internetowa
```

## Zobacz także

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Klasa [PictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)