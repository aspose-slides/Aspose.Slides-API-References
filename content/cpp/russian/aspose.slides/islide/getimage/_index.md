---
title: GetImage()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает объект изображения с пользовательским масштабированием.
type: docs
weight: 105
url: /ru/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) метод

Возвращает объект изображения с пользовательским масштабированием.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси x. |
| scaleY | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси y. |

### Возвращаемое значение

Объект Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() метод

Возвращает объект Thumbnail Image (20% реального размера).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Возвращаемое значение

Объект Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) метод

Возвращает объект изображения с указанным размером.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объект Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) метод

Возвращает объект эскизного tiff bitmap с указанными параметрами.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Параметры Tiff. |

### Возвращаемое значение

Объект Image.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) метод

Возвращает объект эскизного Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |

### Возвращаемое значение

Объекты Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) метод

Возвращает объект эскизного Bitmap с пользовательским масштабированием.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| scaleX | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси x. |
| scaleY | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси y. |

### Возвращаемое значение

Объекты Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) метод

Возвращает объект эскизного Bitmap с указанным размером.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объекты Bitmap.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)