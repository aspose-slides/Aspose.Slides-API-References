---
title: ToTiff()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konwertuje podaną prezentację na zestaw obrazów w formacie TIFF.  Jeśli podano nazwę pliku wyjściowego jako \"myPath/myFilename.tiff\", wynik zostanie zapisany jako zestaw plików \"myPath/myFilename_N.tiff\", gdzie N jest numerem slajdu.
type: docs
weight: 66
url: /pl/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) metoda


Konwertuje podaną prezentację na zestaw obrazów w formacie TIFF. 

Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.tiff", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Wejściowa prezentacja. |
| outputFileName | [System::String](../../../system/string/) | Nazwa pliku wyjściowego. |
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) metoda


Konwertuje podaną prezentację do formatu TIFF z niestandardowymi opcjami. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.tiff" i *multipage* jest **false**, wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu. W przeciwnym razie, jeśli *multipage* jest **true**, wynik będzie dokumentem wielostronicowym "myPath/myFilename.tiff".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Wejściowa prezentacja. |
| outputFileName | [System::String](../../../system/string/) | Nazwa pliku wyjściowego. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opcje zapisu TIFF. |
| multipage | **bool** | Określa, czy wygenerowany dokument TIFF ma być wielostronicowy. |
## Uwagi




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [String](../../../system/string/)
* Klasa [Convert](../)
* Klasa [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)