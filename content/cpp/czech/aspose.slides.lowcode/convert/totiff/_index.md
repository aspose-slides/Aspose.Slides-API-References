---
title: ToTiff()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí vstupní prezentaci na sadu obrázků ve formátu TIFF.  Pokud je zadáno výstupní jméno souboru jako \"myPath/myFilename.tiff\", výsledek bude uložen jako sada souborů \"myPath/myFilename_N.tiff\", kde N je číslo snímku.
type: docs
weight: 66
url: /cs/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) metoda

Převádí vstupní prezentaci na sadu obrázků ve formátu TIFF. 

Pokud je zadáno výstupní jméno souboru jako "myPath/myFilename.tiff", výsledek bude uložen jako sada souborů "myPath/myFilename_N.tiff", kde N představuje číslo snímku.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace. |
| outputFileName | [System::String](../../../system/string/) | Výstupní jméno souboru. |

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) metoda

Převádí vstupní prezentaci do formátu TIFF s vlastními možnostmi. Pokud je zadáno výstupní jméno souboru jako "myPath/myFilename.tiff" a *multipage* je **false**, výsledek bude uložen jako sada souborů "myPath/myFilename_N.tiff", kde N představuje číslo snímku. V opačném případě, pokud je *multipage* **true**, výsledek bude vícestránkový dokument "myPath/myFilename.tiff".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace. |
| outputFileName | [System::String](../../../system/string/) | Výstupní jméno souboru. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Možnosti ukládání TIFF. |
| multipage | **bool** | Určuje, zda má být vytvořený dokument TIFF více stránkový. |

## Poznámky

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)