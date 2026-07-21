---
title: AddImage()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет копию изображения из другой презентации.
type: docs
weight: 53
url: /ru/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) метод

Добавляет копию изображения из другой презентации.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Исходное изображение. |

### Возвращаемое значение

Добавленное изображение.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) метод

Добавить изображение в презентацию.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Изображение для добавления. |

### Возвращаемое значение

Добавленное изображение.

## Примечания

Этот метод преобразует метафайлы WMF/EMF в растровое PNG-изображение перед вставкой в презентацию.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) метод

Добавить изображение в презентацию из потока.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Поток, из которого добавляется изображение. |

### Возвращаемое значение

Добавленное изображение.

## Примечания

Этот метод может добавить метафайлы WMF/EMF в презентацию без их преобразования в растровое PNG-изображение.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) метод

Добавить изображение в презентацию из потока.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавляется изображение. |

### Возвращаемое значение

Добавленное изображение.

## Примечания

Этот метод может добавить метафайлы WMF/EMF в презентацию без их преобразования в растровое PNG-изображение.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) метод

Создаёт и добавляет изображение в презентацию из потока.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавляется файл изображения. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Поведение, которое будет применено к потоку. |

### Возвращаемое значение

Добавлен [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) метод

Добавляет изображение в презентацию из указанного буфера.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер. |

### Возвращаемое значение

Добавленное изображение.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) метод

Добавить изображение в презентацию из объекта Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | объект изображения Svg [ISvgImage](../../isvgimage/) |

### Возвращаемое значение

Добавленное изображение.

## Смотрите также

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)