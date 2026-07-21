---
title: ReadPresentation()
second_title: Aspose.Slides для справки по API C++
description: Читает существующую презентацию из массива
type: docs
weight: 40
url: /ru/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) метод

Читает существующую презентацию из массива

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив для чтения |

### Возвращаемое значение

Прочитанная презентация

## PresentationFactory::ReadPresentation(System::SharedPtr\<ILoadOptions\>) метод

Читает существующую презентацию из массива с дополнительными параметрами загрузки

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив для чтения |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Параметры загрузки |

### Возвращаемое значение

Прочитанная презентация

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) метод

Читает существующую презентацию из потока

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток ввода для чтения |

### Возвращаемое значение

Прочитанная презентация

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) метод

Читает существующую презентацию из потока с дополнительными параметрами загрузки

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток ввода для чтения |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Параметры загрузки |

### Возвращаемое значение

Прочитанная презентация

## PresentationFactory::ReadPresentation(System::String) метод

Читает существующую презентацию из файла

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Имя файла |

### Возвращаемое значение

Прочитанная презентация

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) метод

Читает существующую презентацию из файла с дополнительными параметрами загрузки

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
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
* Class [IPresentation](../../ipresentation/)
* Class [PresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)