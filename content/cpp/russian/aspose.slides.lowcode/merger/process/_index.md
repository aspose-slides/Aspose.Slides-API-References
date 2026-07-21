---
title: Process()
second_title: Aspose.Slides для C++ справочник API
description: Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.
type: docs
weight: 1
url: /ru/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) метод

Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Массив имён входных файлов презентаций. |
| outputFileName | [System::String](../../../system/string/) | Имя выходного файла результирующей объединённой презентации. |

## Примечания

```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) метод

Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Массив имён входных файлов презентаций. |
| outputFileName | [System::String](../../../system/string/) | Имя выходного файла результирующей объединённой презентации. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Дополнительные параметры, определяющие, как сохраняется объединённая презентация. |

## Примечания

```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) метод

Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Массив имён входных файлов презентаций. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Выходной поток. |

## Примечания

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) метод

Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Массив имён входных файлов презентаций. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Выходной поток. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Дополнительные параметры, определяющие, как сохраняется объединённая презентация. |

## Примечания

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Merger](../)
* Класс [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Библиотека [Aspose.Slides](../../../)