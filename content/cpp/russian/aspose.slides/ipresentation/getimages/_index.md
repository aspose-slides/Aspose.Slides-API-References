---
title: GetImages()
second_title: Aspose.Slides для C++ – справочник API
description: Возвращает объекты Thumbnail Image для всех слайдов презентации.
type: docs
weight: 417
url: /ru/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) метод


Возвращает объекты Thumbnail Image для всех слайдов презентации.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |

### Возвращаемое значение

Объекты Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) метод


Возвращает объекты Thumbnail Bitmap для указанных слайдов презентации.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Массив позиций слайдов, начиная с 1. |

### Возвращаемое значение

Объекты Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) метод


Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| scaleX | **float** | Значение, на которое масштабировать этот Thumbnail по оси X. |
| scaleY | **float** | Значение, на которое масштабировать этот Thumbnail по оси Y. |

### Возвращаемое значение

Объекты Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) метод


Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Массив позиций слайдов, начиная с 1. |
| scaleX | **float** | Значение, на которое масштабировать этот Thumbnail по оси X. |
| scaleY | **float** | Значение, на которое масштабировать этот Thumbnail по оси Y. |

### Возвращаемое значение

Объекты Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) метод


Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объекты Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) метод


Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Массив позиций слайдов, начиная с 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объекты Bitmap.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IImage](../../iimage/)
* Класс [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Класс [IPresentation](../)
* Класс [Size](../../../system.drawing/size/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)