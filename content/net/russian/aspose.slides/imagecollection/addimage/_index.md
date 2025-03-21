---
title: AddImage
second_title: Справочник по API Aspose.Slides для .NET
description: Добавляет копию изображения из другой презентации.
type: docs
weight: 50
url: /ru/aspose.slides/imagecollection/addimage/
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
* class [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

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
* class [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(MemoryStream) {#addimage_4}

Добавить изображение в презентацию из потока.

```csharp
public IPPImage AddImage(MemoryStream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | MemoryStream | Поток, из которого нужно добавить изображение. |

### Возвращаемое значение

Добавлено изображение.

### Примечания

Этот метод позволяет добавлять в презентацию метафайлы WMF/EMF без преобразования их в растровое изображение PNG.

### Смотрите также

* interface [IPPImage](../../ippimage)
* class [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
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
* class [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
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
* class [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
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
* class [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

---

## AddImage(ISvgImage) {#addimage_1}

Добавить изображение в презентацию из объекта Svg.

```csharp
public IPPImage AddImage(ISvgImage svgImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | ISvgImage | Объект изображения Svg[`ISvgImage`](../../isvgimage) |

### Возвращаемое значение

Добавлено изображение.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Когда параметр svgImage имеет значение null. |

### Смотрите также

* interface [IPPImage](../../ippimage)
* interface [ISvgImage](../../isvgimage)
* class [ImageCollection](../../imagecollection)
* пространство имен [Aspose.Slides](../../imagecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
