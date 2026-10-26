---
title: Process()
second_title: Riferimento API di Aspose.Slides per C++
description: Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.
type: docs
weight: 1
url: /it/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) metodo

Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Un array dei nomi dei file di presentazione di input. |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output della presentazione unita risultante. |

## Osservazioni

```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) metodo

Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Un array dei nomi dei file di presentazione di input. |
| outputFileName | [System::String](../../../system/string/) | Il nome del file di output della presentazione unita risultante. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Le opzioni aggiuntive che definiscono come la presentazione unita viene salvata. |

## Osservazioni

```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) metodo

Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Un array dei nomi dei file di presentazione di input. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Il flusso di output. |

## Osservazioni

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) metodo

Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Un array dei nomi dei file di presentazione di input. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Il flusso di output. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Le opzioni aggiuntive che definiscono come la presentazione unita viene salvata. |

## Osservazioni

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Merger](../)
* Classe [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::LowCode](../../)
* Libreria [Aspose.Slides](../../../)