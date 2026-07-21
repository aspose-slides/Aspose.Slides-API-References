---
title: GetImages()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает объекты Image для всех слайдов презентации.
type: docs
weight: 456
url: /ru/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method

Возвращает объекты Image для всех слайдов презентации.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры Tiff. |

### Возвращаемое значение

Объекты Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method

Возвращает объекты Thumbnail Image для указанных слайдов презентации.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Массив с позициями слайдов, начиная с 1. |

### Возвращаемое значение

Объекты Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры Tiff. |
| scaleX | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси X. |
| scaleY | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси Y. |

### Возвращаемое значение

Объекты Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method

Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Массив с позициями слайдов, начиная с 1. |
| scaleX | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси X. |
| scaleY | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси Y. |

### Возвращаемое значение

Объекты Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объекты Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method

Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Массив с позициями слайдов, начиная с 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объекты Image.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [Presentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)