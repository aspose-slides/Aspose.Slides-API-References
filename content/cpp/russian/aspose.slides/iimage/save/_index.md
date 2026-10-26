---
title: Save()
second_title: Справочник API Aspose.Slides для C++
description: Сохраняет изображение в файл.
type: docs
weight: 40
url: /ru/aspose.slides/iimage/save/
---
## IImage::Save(System::String) метод

Сохраняет изображение в файл.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Путь к файлу, в который будет сохранено изображение. |

## IImage::Save(System::String, ImageFormat) метод

Сохраняет изображение в файл в указанном формате.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Путь к файлу, в который будет сохранено изображение. |
| format | [ImageFormat](../../imageformat/) | Формат изображения. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) метод

Сохраняет изображение в поток в указанном формате.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, в который будет сохранено изображение. |
| format | [ImageFormat](../../imageformat/) | Формат изображения. |

## IImage::Save(System::String, ImageFormat, int32_t) метод

Сохраняет изображение в файл в указанном формате и качестве.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Путь к файлу, в который будет сохранено изображение. |
| format | [ImageFormat](../../imageformat/) | Формат изображения. |
| quality | **int32_t** | Качество сохраняемого изображения (от 0 до 100).  

 Этот параметр влияет только на сохранение в [ImageFormat::Jpeg](../../imageformat/); для всех остальных форматов он игнорируется. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) метод

Сохраняет изображение в поток в указанном формате и качестве.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, в который будет сохранено изображение. |
| format | [ImageFormat](../../imageformat/) | Формат изображения. |
| quality | **int32_t** | Качество сохраняемого изображения (от 0 до 100).  

 Этот параметр влияет только на сохранение в [ImageFormat::Jpeg](../../imageformat/); для всех остальных форматов он игнорируется. |

## Смотрите также

* Перечисление [ImageFormat](../../imageformat/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [IImage](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)