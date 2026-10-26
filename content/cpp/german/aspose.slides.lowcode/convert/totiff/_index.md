---
title: ToTiff()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert die Eingabepäsentation in eine Menge von TIFF-Format-Bildern.  Wenn der Ausgabedateiname als \"myPath/myFilename.tiff\" angegeben wird, wird das Ergebnis als eine Menge von \"myPath/myFilename_N.tiff\" Dateien gespeichert, wobei N eine Foliennummer ist.
type: docs
weight: 66
url: /de/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) Methode


Konvertiert die Eingabepäsentation in eine Menge von TIFF-Format-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.tiff\" angegeben wird, wird das Ergebnis als eine Menge von Dateien \"myPath/myFilename_N.tiff\" gespeichert, wobei N eine Foliennummer ist.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Eingabepäsentation. |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname. |
## Anmerkungen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) Methode


Konvertiert die Eingabepäsentation in das TIFF-Format mit benutzerdefinierten Optionen. Wenn der Ausgabedateiname als \"myPath/myFilename.tiff\" angegeben wird und *multipage* **false** ist, wird das Ergebnis als eine Menge von Dateien \"myPath/myFilename_N.tiff\" gespeichert, wobei N eine Foliennummer ist. Andernfalls, wenn *multipage* **true** ist, wird das Ergebnis ein mehrseitiges Dokument \"myPath/myFilename.tiff\" sein.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Eingabepäsentation. |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Die TIFF-Speicheroptionen. |
| multipage | **bool** | Gibt an, ob das erzeugte TIFF-Dokument mehrseitig sein soll. |
## Anmerkungen




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [String](../../../system/string/)
* Klasse [Convert](../)
* Klasse [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namensraum [Aspose::Slides::LowCode](../../)
* Bibliothek [Aspose.Slides](../../../)