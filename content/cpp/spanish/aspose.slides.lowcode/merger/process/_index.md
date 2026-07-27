---
title: Process()
second_title: Referencia de la API de Aspose.Slides para C++
description: Fusiona varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.
type: docs
weight: 1
url: /es/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) método


Fusiona varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Una matriz de los nombres de archivo de presentación de entrada. |
| outputFileName | [System::String](../../../system/string/) | El nombre de archivo de salida del archivo de presentación fusionado resultante. |
## Observaciones




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) método


Fusiona varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Una matriz de los nombres de archivo de presentación de entrada. |
| outputFileName | [System::String](../../../system/string/) | El nombre de archivo de salida del archivo de presentación fusionado resultante. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Las opciones adicionales que definen cómo se guarda la presentación fusionada. |
## Observaciones 




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) método


Fusiona varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Una matriz de los nombres de archivo de presentación de entrada. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | El flujo de salida. |
## Observaciones 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) método


Fusiona varias presentaciones de PowerPoint del mismo formato en un solo archivo de presentación.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Una matriz de los nombres de archivo de presentación de entrada. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | El flujo de salida. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Las opciones adicionales que definen cómo se guarda la presentación fusionada. |
## Observaciones 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [Merger](../)
* Clase [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)