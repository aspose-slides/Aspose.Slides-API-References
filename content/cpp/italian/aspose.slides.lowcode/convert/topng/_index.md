---
title: ToPng()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la presentazione di input in un insieme di immagini in formato PNG. Se il nome del file di output è fornito come \"myPath/myFilename.png\", il risultato verrà salvato come un insieme di file \"myPath/myFilename_N.png\", dove N è il numero della diapositiva.
type: docs
weight: 53
url: /it/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) metodo

Converte la presentazione di input in un insieme di immagini in formato PNG. 

 Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentazione di input. |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output. |
## Note




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metodo


Converte la presentazione di input in un insieme di immagini in formato PNG. 

 Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentazione di input |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | La dimensione di ogni immagine generata. |
## Note




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metodo


Converte la presentazione di input in un insieme di immagini in formato PNG. 

 Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentazione di input. |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output. |
| scale | **float** | Il fattore di scala applicato alle immagini di output rispetto alle dimensioni originali della diapositiva. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Le opzioni di rendering. |
## Note




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [Size](../../../system.drawing/size/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Spazio dei nomi [Aspose::Slides::LowCode](../../)
* Libreria [Aspose.Slides](../../../)