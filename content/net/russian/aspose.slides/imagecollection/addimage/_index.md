---
title: AddImage
second_title: Справочник по API Aspose.Slides для .NET
description: Добавляет копию изображения из другой презентации.
type: docs
weight: 50
url: /ru/aspose.slides/imagecollection/addimage/
---

## AddImage(IPPImage) {#addimage_1}

Добавляет копию изображения из другой презентации.

```csharp
public IPPImage AddImage(IPPImage imageSource)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSource | IPPImage | Исходное изображение. |

### Возвращаемое значение

Добавленное изображение.

### См. Также

* интерфейс [IPPImage](../../ippimage)
* класс [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(IImage) {#addimage}

Добавить изображение в презентацию.

```csharp
public IPPImage AddImage(IImage image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | IImage | Изображение для добавления. |

### Возвращаемое значение

Добавленное изображение.

### Примечания

Этот метод преобразует метафайлы WMF/EMF в растровое PNG изображение перед вставкой в презентацию.

### См. Также

* интерфейс [IPPImage](../../ippimage)
* интерфейс [IImage](../../iimage)
* класс [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(MemoryStream) {#addimage_5}

Добавить изображение в презентацию из потока.

```csharp
public IPPImage AddImage(MemoryStream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | MemoryStream | Поток, из которого добавляется изображение. |

### Возвращаемое значение

Добавленное изображение.

### Примечания

Этот метод может добавить метафайлы WMF/EMF в презентацию без их преобразования в растровое PNG изображение.

### См. Также

* интерфейс [IPPImage](../../ippimage)
* класс [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(Stream) {#addimage_6}

Добавить изображение в презентацию из потока.

```csharp
public IPPImage AddImage(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого добавляется изображение. |

### Возвращаемое значение

Добавленное изображение.

### Примечания

Этот метод может добавить метафайлы WMF/EMF в презентацию без их преобразования в растровое PNG изображение.

### См. Также

* интерфейс [IPPImage](../../ippimage)
* класс [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(Stream, LoadingStreamBehavior) {#addimage_7}

Создает и добавляет изображение в презентацию из потока.

```csharp
public IPPImage AddImage(Stream stream, LoadingStreamBehavior loadingStreamBehavior)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого добавляется файл изображения. |
| loadingStreamBehavior | LoadingStreamBehavior | Поведение, которое будет применено к потоку. |

### Возвращаемое значение

Добавленное [`IPPImage`](../../ippimage).

### См. Также

* интерфейс [IPPImage](../../ippimage)
* перечисление [LoadingStreamBehavior](../../loadingstreambehavior)
* класс [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(byte[]) {#addimage_3}

Добавляет изображение в презентацию из указанного буфера.

```csharp
public IPPImage AddImage(byte[] buffer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | Byte[] | Буфер. |

### Возвращаемое значение

Добавленное изображение.

### См. Также

* интерфейс [IPPImage](../../ippimage)
* класс [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(ISvgImage) {#addimage_2}

Добавить изображение в презентацию из объекта Svg.

```csharp
public IPPImage AddImage(ISvgImage svgImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | ISvgImage | Объект изображения Svg [`ISvgImage`](../../isvgimage) |

### Возвращаемое значение

Добавленное изображение.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Когда параметр svgImage равен null. |

### См. Также

* интерфейс [IPPImage](../../ippimage)
* интерфейс [ISvgImage](../../isvgimage)
* класс [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)