---
title: ToJpeg()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje podaną prezentację na zestaw obrazów w formacie JPEG. Jeśli nazwa pliku wyjściowego zostanie podana jako \"myPath/myFilename.jpeg\", wynik zostanie zapisany jako zestaw plików \"myPath/myFilename_N.jpeg\", gdzie N jest numerem slajdu.
type: docs
weight: 40
url: /pl/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) metoda

Konwertuje podaną prezentację na zestaw obrazów w formacie JPEG.  

Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Wejściowa prezentacja. |
| outputFileName | [System::String](../../../system/string/) | Nazwa pliku wyjściowego. |

## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metoda

Konwertuje podaną prezentację na zestaw obrazów w formacie JPEG.  

Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Wejściowa prezentacja |
| outputFileName | [System::String](../../../system/string/) | Nazwa pliku wyjściowego. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Rozmiar każdego wygenerowanego obrazu. |

## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metoda

Konwertuje podaną prezentację na zestaw obrazów w formacie JPEG.  

Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Wejściowa prezentacja. |
| outputFileName | [System::String](../../../system/string/) | Nazwa pliku wyjściowego. |
| scale | **float** | Współczynnik skalowania zastosowany do obrazów wyjściowych względem oryginalnego rozmiaru slajdu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opcje renderowania. |

## Uwagi




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [String](../../../system/string/)
* Klasa [Convert](../)
* Klasa [Size](../../../system.drawing/size/)
* Klasa [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)