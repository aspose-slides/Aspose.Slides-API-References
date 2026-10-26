---
title: GetImage()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает объект изображения с пользовательским масштабированием.
type: docs
weight: 105
url: /ru/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) метод


Возвращает объект Image с пользовательским масштабированием.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | **float** | Значение, на которое следует масштабировать эту миниатюру по оси X. |
| scaleY | **float** | Значение, на которое следует масштабировать эту миниатюру по оси Y. |

### Возвращаемое значение

Объект Image [IImage](../../iimage/)

## ISlide::GetImage() метод


Возвращает объект миниатюрного Image (20% от реального размера).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Возвращаемое значение

Объект Image [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) метод


Возвращает объект Image с указанным размером.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объект Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) метод


Возвращает объект bitmap изображения tiff миниатюры с указанными параметрами.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Параметры Tiff. |

### Возвращаемое значение

Объект Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) метод


Возвращает объект миниатюрного Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |

### Возвращаемое значение

Объект Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) метод


Возвращает объект миниатюрного Bitmap с пользовательским масштабированием.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| scaleX | **float** | Значение, на которое следует масштабировать эту миниатюру по оси X. |
| scaleY | **float** | Значение, на которое следует масштабировать эту миниатюру по оси Y. |

### Возвращаемое значение

Объект Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) метод


Возвращает объект миниатюрного Bitmap с указанным размером.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объект Image [IImage](../../iimage/)

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IImage](../../iimage/)
* Класс [ISlide](../)
* Класс [Size](../../../system.drawing/size/)
* Класс [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Класс [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)