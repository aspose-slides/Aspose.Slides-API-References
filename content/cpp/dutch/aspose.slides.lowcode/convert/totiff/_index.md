---
title: ToTiff()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de invoerpresentatie naar een set TIFF-formaat afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als \"myPath/myFilename.tiff\", wordt het resultaat opgeslagen als een set van \"myPath/myFilename_N.tiff\" bestanden, waarbij N een dia-nummer is.
type: docs
weight: 66
url: /nl/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) methode


Converteert de invoerpresentatie naar een set TIFF-formaat afbeeldingen. 

Als de uitvoerbestandsnaam wordt opgegeven als \"myPath/myFilename.tiff\", wordt het resultaat opgeslagen als een set van \"myPath/myFilename_N.tiff\" bestanden, waarbij N een dia-nummer is.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De invoerpresentatie. |
| outputFileName | [System::String](../../../system/string/) | De uitvoerbestandsnaam. |
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) methode


Converteert de invoerpresentatie naar TIFF-formaat met aangepaste opties. Als de uitvoerbestandsnaam wordt opgegeven als \"myPath/myFilename.tiff\" en *multipage* **false** is, wordt het resultaat opgeslagen als een set van \"myPath/myFilename_N.tiff\" bestanden, waarbij N een dia-nummer is. Anders, als *multipage* **true** is, wordt het resultaat een meer-pagina \"myPath/myFilename.tiff\" document.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De invoerpresentatie. |
| outputFileName | [System::String](../../../system/string/) | De uitvoerbestandsnaam. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | De TIFF-opslagopties. |
| multipage | **bool** | Geeft aan of het gegenereerde TIFF-document een meer-pagina moet zijn. |
## Opmerkingen




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [String](../../../system/string/)
* Klasse [Convert](../)
* Klasse [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)