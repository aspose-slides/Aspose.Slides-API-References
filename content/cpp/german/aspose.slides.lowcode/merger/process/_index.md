---
title: Process()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.
type: docs
weight: 1
url: /de/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) Methode


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ein Array der Eingabe-Präsentationsdateinamen. |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname der resultierenden zusammengeführten Präsentationsdatei. |
## Bemerkungen




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) Methode


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ein Array der Eingabe-Präsentationsdateinamen. |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname der resultierenden zusammengeführten Präsentationsdatei. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Die zusätzlichen Optionen, die festlegen, wie die zusammengeführte Präsentation gespeichert wird. |
## Bemerkungen




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) Methode


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ein Array der Eingabe-Präsentationsdateinamen. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Der Ausgabestream. |
## Bemerkungen




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) Methode


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ein Array der Eingabe-Präsentationsdateinamen. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Der Ausgabestream. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Die zusätzlichen Optionen, die festlegen, wie die zusammengeführte Präsentation gespeichert wird. |
## Bemerkungen




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Merger](../)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)