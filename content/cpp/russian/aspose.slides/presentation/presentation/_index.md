---
title: Presentation()
second_title: Aspose.Slides для C++ – справка по API
description: Этот конструктор создает новую презентацию с нуля. Созданная презентация содержит один пустой слайд.
type: docs
weight: 417
url: /ru/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() конструктор

Этот конструктор создает новую презентацию с нуля. Созданная презентация содержит один пустой слайд.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) конструктор

Этот конструктор создает новую презентацию с нуля. Созданная презентация содержит один пустой слайд.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Дополнительные параметры загрузки. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) конструктор

Этот конструктор является основным механизмом чтения существующего [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток. |

## Примечания

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) конструктор

Этот конструктор является основным механизмом чтения существующего [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Дополнительные параметры загрузки. |

## Presentation::Presentation(System::String) конструктор

Этот конструктор получает путь к исходному файлу, из которого читаются содержимое [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Входной файл. |

## Примечания

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) конструктор

Этот конструктор получает путь к исходному файлу, из которого читаются содержимое [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Входной файл. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Дополнительные параметры загрузки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)