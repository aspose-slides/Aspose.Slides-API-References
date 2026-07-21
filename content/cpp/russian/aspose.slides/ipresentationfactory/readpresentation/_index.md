---
title: ReadPresentation()
second_title: Справочник API Aspose.Slides для C++
description: Считывает существующую презентацию из массива
type: docs
weight: 27
url: /ru/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) метод

Считывает существующую презентацию из массива

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив для чтения |

### Возвращаемое значение

Прочитанная презентация

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) метод

Считывает существующую презентацию из массива с дополнительными параметрами загрузки

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив для чтения |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Параметры загрузки |

### Возвращаемое значение

Прочитанная презентация

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) метод

Считывает существующую презентацию из потока

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток для чтения |

### Возвращаемое значение

Прочитанная презентация

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) метод

Считывает существующую презентацию из потока с дополнительными параметрами загрузки

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток для чтения |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Параметры загрузки |

### Возвращаемое значение

Прочитанная презентация

## IPresentationFactory::ReadPresentation(System::String) метод

Считывает существующую презентацию из файла

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Имя файла |

### Возвращаемое значение

Прочитанная презентация

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) метод

Считывает существующую презентацию из потока с дополнительными параметрами загрузки

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Имя файла |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Параметры загрузки |

### Возвращаемое значение

Прочитанная презентация

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [IPresentation](../../ipresentation/)
* Класс [IPresentationFactory](../)
* Класс [ILoadOptions](../../iloadoptions/)
* Класс [Stream](../../../system.io/stream/)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)