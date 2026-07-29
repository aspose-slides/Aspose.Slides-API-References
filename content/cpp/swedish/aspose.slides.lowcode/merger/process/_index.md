---
title: Process()
second_title: Aspose.Slides för C++ API-referens
description: Sammanfogar flera PowerPoint-presentationer av samma format till en enda presentationsfil.
type: docs
weight: 1
url: /sv/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) metod


Sammanfogar flera PowerPoint-presentationer av samma format till en enda presentationsfil.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | En array av inmatningspresentationernas filnamn. |
| outputFileName | [System::String](../../../system/string/) | Filnamnet för den resulterande sammanslagna presentationsfilen. |
## Anmärkningar




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) metod


Sammanfogar flera PowerPoint-presentationer av samma format till en enda presentationsfil.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | En array av inmatningspresentationernas filnamn. |
| outputFileName | [System::String](../../../system/string/) | Filnamnet för den resulterande sammanslagna presentationsfilen. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | De ytterligare alternativ som definierar hur den sammanslagna presentationen sparas. |
## Anmärkningar




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) metod


Sammanfogar flera PowerPoint-presentationer av samma format till en enda presentationsfil.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | En array av inmatningspresentationernas filnamn. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Utdatastreamen. |
## Anmärkningar 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) metod


Sammanfogar flera PowerPoint-presentationer av samma format till en enda presentationsfil.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | En array av inmatningspresentationernas filnamn. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Utdatastreamen. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | De ytterligare alternativ som definierar hur den sammanslagna presentationen sparas. |
## Anmärkningar 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Se också

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Merger](../)
* Klass [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)