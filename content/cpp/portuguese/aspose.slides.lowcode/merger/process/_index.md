---
title: Process()
second_title: Referência da API Aspose.Slides para C++
description: Mescla várias apresentações do PowerPoint com o mesmo formato em um único arquivo de apresentação.
type: docs
weight: 1
url: /pt/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) método


Mescla várias apresentações do PowerPoint do mesmo formato em um único arquivo de apresentação.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Um array com os nomes dos arquivos de apresentação de entrada. |
| outputFileName | [System::String](../../../system/string/) | O nome do arquivo de saída da apresentação mesclada resultante. |
## Observações




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) método
Mescla múltiplas apresentações PowerPoint do mesmo formato em um único arquivo de apresentação.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Um array com os nomes dos arquivos de apresentação de entrada. |
| outputFileName | [System::String](../../../system/string/) | O nome do arquivo de saída da apresentação mesclada resultante. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | As opções adicionais que definem como a apresentação mesclada será salva. |
## Observações




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) método


Mescla múltiplas apresentações PowerPoint do mesmo formato em um único arquivo de apresentação.
```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Um array contendo os nomes dos arquivos de apresentação de entrada. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | O fluxo de saída. |
## Observações




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) method


Mescla múltiplas apresentações do PowerPoint do mesmo formato em um único arquivo de apresentação.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Um array contendo os nomes dos arquivos de apresentação de entrada. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | O fluxo de saída. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | As opções adicionais que definem como a apresentação mesclada é salva. |
## Observações




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Merger](../)
* Classe [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Classe [Stream](../../../system.io/stream/)
* Espaço de nomes [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)