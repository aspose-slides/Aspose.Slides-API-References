---
title: ToTiff()
second_title: Aspose.Slides for C++ API Referencia
description: Átalakítja a bemeneti prezentációt TIFF formátumú képek halmazává.  Ha a kimeneti fájlnév \"myPath/myFilename.tiff\", az eredmény \"myPath/myFilename_N.tiff\" fájlok halmazaként lesz mentve, ahol N egy dia szám.
type: docs
weight: 66
url: /hu/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) metódus

Átalakítja a bemeneti prezentációt TIFF formátumú képek halmazává.  

Ha a kimeneti fájlnév „myPath/myFilename.tiff”-ként van megadva, az eredmény „myPath/myFilename_N.tiff” fájlok halmazaként lesz mentve, ahol N egy dia száma.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A bemeneti prezentáció. |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájlnév. |

## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) metódus

Átalakítja a bemeneti prezentációt TIFF formátumba egyéni beállításokkal. Ha a kimeneti fájlnév „myPath/myFilename.tiff” és a *multipage* **false**, az eredmény „myPath/myFilename_N.tiff” fájlok halmazaként lesz mentve, ahol N egy dia száma. Ha a *multipage* **true**, az eredmény egy többoldalas „myPath/myFilename.tiff” dokumentum lesz.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A bemeneti prezentáció. |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájlnév. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | A TIFF mentési beállítások. |
| multipage | **bool** | Megadja, hogy az előállított TIFF dokumentumnak többoldalasnak kell-e lennie. |

## Megjegyzések

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)