---
title: SvgImage()
second_title: Справочник API Aspose.Slides for C++
description: Создаёт новый объект SvgImage.
type: docs
weight: 53
url: /ru/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) конструктор

Создаёт новый объект [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Данные Svg. |

## SvgImage::SvgImage(System::String) конструктор

Создаёт новый объект [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Содержимое Svg. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) конструктор

Создаёт новый объект [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток Svg. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) конструктор

Создаёт новый объект [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Данные Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | [System::String](../../../system/string/) | Базовый URI указанного Svg. Используется для разрешения относительных ссылок. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) конструктор

Создаёт новый объект [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Содержимое Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | [System::String](../../../system/string/) | Базовый URI указанного Svg. Используется для разрешения относительных ссылок. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) конструктор

Создаёт новый объект [SvgImage](../).

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | [System::String](../../../system/string/) | Базовый URI указанного Svg. Используется для разрешения относительных ссылок. |

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [SvgImage](../)
* Класс [String](../../../system/string/)
* Класс [Stream](../../../system.io/stream/)
* Класс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)