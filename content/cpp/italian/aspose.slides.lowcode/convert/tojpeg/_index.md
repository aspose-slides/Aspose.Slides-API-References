---
title: ToJpeg()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la presentazione di input in un insieme di immagini in formato JPEG.  Se il nome del file di output viene fornito come \"myPath/myFilename.jpeg\", il risultato verrà salvato come un insieme di file \"myPath/myFilename_N.jpeg\", dove N è il numero della diapositiva.
type: docs
weight: 40
url: /it/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) metodo

Converte la presentazione di input in un insieme di immagini in formato JPEG.

 Se il nome del file di output è fornito come \"myPath/myFilename.jpeg\", il risultato verrà salvato come un insieme di file \"myPath/myFilename_N.jpeg\", dove N è il numero della diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentazione di input. |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output. |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metodo

Converte la presentazione di input in un insieme di immagini in formato JPEG.

 Se il nome del file di output è fornito come \"myPath/myFilename.jpeg\", il risultato verrà salvato come un insieme di file \"myPath/myFilename_N.jpeg\", dove N è il numero della diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentazione di input |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | La dimensione di ogni immagine generata. |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metodo

Converte la presentazione di input in un insieme di immagini in formato JPEG.

 Se il nome del file di output è fornito come \"myPath/myFilename.jpeg\", il risultato verrà salvato come un insieme di file \"myPath/myFilename_N.jpeg\", dove N è il numero della diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentazione di input. |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output. |
| scale | **float** | Il fattore di scala applicato alle immagini di output rispetto alla dimensione originale della diapositiva. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Le opzioni di rendering. |
## Osservazioni

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [Size](../../../system.drawing/size/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Libreria [Aspose.Slides](../../../)