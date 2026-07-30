---
title: Process()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Sloučí více PowerPoint prezentací stejného formátu do jediného souboru prezentace.
type: docs
weight: 1
url: /cs/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) metoda

Sloučí více PowerPoint prezentací stejného formátu do jediného souboru prezentace.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Pole názvů vstupních souborů prezentace. |
| outputFileName | [System::String](../../../system/string/) | Název výstupního souboru výsledné sloučené prezentace. |

## Poznámky

```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) metoda

Sloučí více PowerPoint prezentací stejného formátu do jediného souboru prezentace.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Pole názvů vstupních souborů prezentace. |
| outputFileName | [System::String](../../../system/string/) | Název výstupního souboru výsledné sloučené prezentace. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Další možnosti, které definují, jak je sloučená prezentace uložena. |

## Poznámky

```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) metoda

Sloučí více PowerPoint prezentací stejného formátu do jediného souboru prezentace.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Pole názvů vstupních souborů prezentace. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Výstupní proud. |

## Poznámky

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) metoda

Sloučí více PowerPoint prezentací stejného formátu do jediného souboru prezentace.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Pole názvů vstupních souborů prezentace. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Výstupní proud. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Další možnosti, které definují, jak je sloučená prezentace uložena. |

## Poznámky

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Merger](../)
* Třída [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)