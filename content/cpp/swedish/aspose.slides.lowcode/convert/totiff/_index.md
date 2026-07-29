---
title: ToTiff()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna presentationen till en uppsättning TIFF-formatbilder. Om utskriftsfilnamnet anges som \"myPath/myFilename.tiff\" sparas resultatet som en uppsättning av \"myPath/myFilename_N.tiff\"-filer, där N är bildnumret.
type: docs
weight: 66
url: /sv/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) metod


Konverterar den angivna presentationen till en uppsättning TIFF-formatbilder. 

Om utskriftsfilnamnet anges som \"myPath/myFilename.tiff\" sparas resultatet som en uppsättning av \"myPath/myFilename_N.tiff\"-filer, där N är bildnumret.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Den angivna presentationen. |
| outputFileName | [System::String](../../../system/string/) | Utskriftsfilnamnet. |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) metod


Konverterar den angivna presentationen till TIFF-format med anpassade alternativ. Om utskriftsfilnamnet anges som \"myPath/myFilename.tiff\" och *multipage* är **false**, sparas resultatet som en uppsättning av \"myPath/myFilename_N.tiff\"-filer, där N är bildnumret. Annars, om *multipage* är **true**, blir resultatet ett fler sidigt \"myPath/myFilename.tiff\"-dokument.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Den angivna presentationen. |
| outputFileName | [System::String](../../../system/string/) | Utskriftsfilnamnet. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Alternativen för TIFF-sparande. |
| multipage | **bool** | Anger om det genererade TIFF-dokumentet ska vara flersidigt. |
## Anmärkningar




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [String](../../../system/string/)
* Klass [Convert](../)
* Klass [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)