---
title: Process()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot een enkel presentatiedocument.
type: docs
weight: 1
url: /nl/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) methode


Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatiedocument.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Een array met de bestandsnamen van de invoerpresentaties. |
| outputFileName | [System::String](../../../system/string/) | De bestandsnaam van het samengevoegde presentatiedocument. |
## Opmerkingen




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) methode


Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatiedocument.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Een array met de bestandsnamen van de invoerpresentaties. |
| outputFileName | [System::String](../../../system/string/) | De bestandsnaam van het samengevoegde presentatiedocument. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | De bijkomende opties die definiëren hoe de samengevoegde presentatie wordt opgeslagen. |
## Opmerkingen




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) methode


Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatiedocument.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Een array met de bestandsnamen van de invoerpresentaties. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | De uitvoerstroom. |
## Opmerkingen 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) methode


Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatiedocument.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Een array met de bestandsnamen van de invoerpresentaties. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | De uitvoerstroom. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | De bijkomende opties die definiëren hoe de samengevoegde presentatie wordt opgeslagen. |
## Opmerkingen 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Merger](../)
* Klasse [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)