---
title: AddImage
second_title: Справочник по API Aspose.Slides для .NET
description: Добавить изображение в презентацию.
type: docs
weight: 20
url: /ru/aspose.slides/iimagecollection/addimage/
---
## AddImage(Image) {#addimage_3}

Добавить изображение в презентацию.

```csharp
public IPPImage AddImage(Image image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Image | Изображение для добавления. |

### Возвращаемое значение

Добавлено изображение.

### Примечания

Этот метод преобразует метафайлы WMF/EMF в растровое изображение PNG перед вставкой в презентацию.

### Смотрите также

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* пространство имен [Aspose.Slides](../../iimagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(MemoryStream) {#addimage_4}

Добавляет изображение из потока памяти.

```csharp
public IPPImage AddImage(MemoryStream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | MemoryStream | Поток памяти. |

### Возвращаемое значение

Добавлено изображение.

### Смотрите также

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* пространство имен [Aspose.Slides](../../iimagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(Stream) {#addimage_5}

Добавить изображение в презентацию из потока.

```csharp
public IPPImage AddImage(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого нужно добавить изображение. |

### Возвращаемое значение

Добавлено изображение.

### Примечания

Этот метод позволяет добавлять в презентацию метафайлы WMF/EMF без преобразования их в растровое изображение PNG.

### Смотрите также

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* пространство имен [Aspose.Slides](../../iimagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(Stream, LoadingStreamBehavior) {#addimage_6}

Создает и добавляет изображение в презентацию из потока.

```csharp
public IPPImage AddImage(Stream stream, LoadingStreamBehavior loadingStreamBehavior)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого нужно добавить файл изображения. |
| loadingStreamBehavior | LoadingStreamBehavior | Поведение, которое будет применяться к потоку. |

### Возвращаемое значение

Добавлен[`IPPImage`](../../ippimage).

### Смотрите также

* interface [IPPImage](../../ippimage)
* enum [LoadingStreamBehavior](../../loadingstreambehavior)
* interface [IImageCollection](../../iimagecollection)
* пространство имен [Aspose.Slides](../../iimagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(byte[]) {#addimage_2}

Добавляет изображение в презентацию из указанного буфера.

```csharp
public IPPImage AddImage(byte[] buffer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | Byte[] | Буфер. |

### Возвращаемое значение

Добавлено изображение.

### Смотрите также

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* пространство имен [Aspose.Slides](../../iimagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(IPPImage) {#addimage}

Добавляет копию изображения из другой презентации.

```csharp
public IPPImage AddImage(IPPImage imageSource)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSource | IPPImage | Исходное изображение. |

### Возвращаемое значение

Добавлено изображение.

### Смотрите также

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* пространство имен [Aspose.Slides](../../iimagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(ISvgImage) {#addimage_1}

Добавить изображение в презентацию из объекта SVG.

```csharp
public IPPImage AddImage(ISvgImage svgImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | ISvgImage | Объект изображения SVG[`ISvgImage`](../../isvgimage) |

### Возвращаемое значение

Добавлено изображение.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Вызывается, когда параметр svgImage имеет значение null. |

### Смотрите также

* interface [IPPImage](../../ippimage)
* interface [ISvgImage](../../isvgimage)
* interface [IImageCollection](../../iimagecollection)
* пространство имен [Aspose.Slides](../../iimagecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
