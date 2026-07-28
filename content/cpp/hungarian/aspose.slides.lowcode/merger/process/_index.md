---
title: Process()
second_title: Aspose.Slides C++ API referencia
description: Több azonos formátumú PowerPoint-prezentációt egyetlen prezentációfájlba egyesít.
type: docs
weight: 1
url: /hu/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) módszer


Összevon több PowerPoint-prezentációt azonos formátumban egyetlen prezentációfájlba.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | A bemeneti prezentációfájlok neveit tartalmazó tömb. |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájl neve az eredményül kapott összevont prezentációfájl számára. |
## Megjegyzések




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) módszer


Összevon több PowerPoint-prezentációt azonos formátumban egyetlen prezentációfájlba.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | A bemeneti prezentációfájlok neveit tartalmazó tömb. |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájl neve az eredményül kapott összevont prezentációfájl számára. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Az extra beállítások, amelyek meghatározzák, hogyan mentődik az összevont prezentáció. |
## Megjegyzések




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) módszer


Összevon több PowerPoint-prezentációt azonos formátumban egyetlen prezentációfájlba.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | A bemeneti prezentációfájlok neveit tartalmazó tömb. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A kimeneti adatfolyam. |
## Megjegyzések




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) módszer


Összevon több PowerPoint-prezentációt azonos formátumban egyetlen prezentációfájlba.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | A bemeneti prezentációfájlok neveit tartalmazó tömb. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A kimeneti adatfolyam. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Az extra beállítások, amelyek meghatározzák, hogyan mentődik az összevont prezentáció. |
## Megjegyzések




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Merger](../)
* Osztály [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)