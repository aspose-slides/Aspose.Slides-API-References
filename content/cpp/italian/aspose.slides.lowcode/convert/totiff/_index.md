---
title: ToTiff()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la presentazione in input in un insieme di immagini in formato TIFF. Se il nome del file di output è fornito come \"myPath/myFilename.tiff\", il risultato verrà salvato come un insieme di file \"myPath/myFilename_N.tiff\", dove N è il numero della diapositiva.
type: docs
weight: 66
url: /it/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) method

Converte la presentazione in input in un insieme di immagini in formato TIFF.

Se il nome del file di output è fornito come "myPath/myFilename.tiff", il risultato verrà salvato come un insieme di "myPath/myFilename_N.tiff" file, dove N è il numero della diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentazione in input. |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output. |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) method

Converte la presentazione in input in formato TIFF con opzioni personalizzate. Se il nome del file di output è fornito come "myPath/myFilename.tiff" e *multipage* è **false**, il risultato verrà salvato come un insieme di "myPath/myFilename_N.tiff" file, dove N è il numero della diapositiva. In caso contrario, se *multipage* è **true**, il risultato sarà un documento TIFF a più pagine "myPath/myFilename.tiff".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentazione in input. |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Le opzioni di salvataggio TIFF. |
| multipage | **bool** | Specifica se il documento TIFF generato deve essere a più pagine. |
## Osservazioni

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Spazio dei nomi [Aspose::Slides::LowCode](../../)
* Libreria [Aspose.Slides](../../../)