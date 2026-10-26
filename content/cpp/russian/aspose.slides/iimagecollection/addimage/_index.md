---
title: AddImage()
second_title: Справочник API Aspose.Slides для C++
description: Добавить изображение в презентацию.
type: docs
weight: 14
url: /ru/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) метод

Добавить изображение в презентацию.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Изображение для добавления. |

### Возвращаемое значение

Добавленное изображение.

## Примечания

Этот метод преобразует метафайлы WMF/EMF в растровое PNG-изображение перед вставкой в презентацию.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) метод

Добавляет изображение из потокa памяти.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Поток памяти. |

### Возвращаемое значение

Добавленное изображение.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) метод

Добавить изображение в презентацию из потока.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавить изображение. |

### Возвращаемое значение

Добавленное изображение.

## Примечания

Этот метод может добавить метафайлы WMF/EMF в презентацию без преобразования их в растровое PNG-изображение.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) метод

Создаёт и добавляет изображение в презентацию из потока.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавить файл изображения. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Поведение, которое будет применено к потоку. |

### Возвращаемое значение

Добавлено [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) метод

Добавляет изображение в презентацию из указанного буфера.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер. |

### Возвращаемое значение

Добавленное изображение.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) метод

Добавляет копию изображения из другой презентации.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Исходное изображение. |

### Возвращаемое значение

Добавленное изображение.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) метод

Добавить изображение в презентацию из SVG-объекта.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG-объект изображения [ISvgImage](../../isvgimage/) |

### Возвращаемое значение

Добавленное изображение.

## См. также

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)