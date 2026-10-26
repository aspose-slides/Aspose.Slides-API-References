---
title: CompressImage()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. Opcjonalnie usuwa także przycięte obszary.
type: docs
weight: 443
url: /pl/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) metoda


Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. Opcjonalnie usuwa także przycięte obszary.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Jeśli true, metoda usunie przycięte obszary obrazu, co może dodatkowo zmniejszyć jego rozmiar. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Docelowa rozdzielczość dla kompresji, określona jako wartość wyliczenia [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Wartość zwracana

Typ **bool** wskazujący, czy obraz został pomyślnie skompresowany. Zwraca ****true****

## Uwagi


Ta metoda zmienia rozmiar i rozdzielczość obrazu podobnie jak funkcja PowerPoint "Picture Format -> Compress Pictures".

jeśli obraz został zmieniony rozmiar lub przycięty, w przeciwnym razie ****false****

. 


Poniższy przykład pokazuje, jak użyć metody **CompressImage**, aby zmniejszyć rozmiar obrazu w prezentacji poprzez ustawienie docelowej rozdzielczości i usunięcie przyciętych obszarów: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Skompresuj obraz do docelowej rozdzielczości 150 DPI (rozdzielczość internetowa) i usuń przycięte obszary
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) metoda


Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. Opcjonalnie usuwa także przycięte obszary.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Jeśli true, metoda usunie przycięte obszary obrazu, co może dodatkowo zmniejszyć jego rozmiar. |
| resolution | **float** | Docelowa rozdzielczość w DPI. Wartość ta musi być dodatnia i określa, jak obraz zostanie zmieniony rozmiarem. |

### Wartość zwracana

Typ **bool** wskazujący, czy obraz został pomyślnie skompresowany. Zwraca ****true****

## Uwagi


Ta metoda zmienia rozmiar i rozdzielczość obrazu podobnie jak funkcja PowerPoint "Picture Format -> Compress Pictures".

jeśli obraz został zmieniony rozmiar lub przycięty, w przeciwnym razie ****false****

. 


Poniższy przykład pokazuje, jak użyć metody **CompressImage**, aby zmniejszyć rozmiar obrazu w prezentacji poprzez ustawienie docelowej rozdzielczości i usunięcie przyciętych obszarów: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Pobiera ramkę obrazu
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Kompresuj obraz do docelowej rozdzielczości 150 DPI (rozdzielczość internetowa) i usuń przycięte obszary
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // rozdzielczość internetowa
```

## Zobacz także

* Wyliczenie [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Klasa [IPictureFillFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)