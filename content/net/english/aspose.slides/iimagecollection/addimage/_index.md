---
title: AddImage
second_title: Aspose.Sildes for .NET API Reference
description: Add an image to a presentation.
type: docs
weight: 20
url: /aspose.slides/iimagecollection/addimage/
---

## AddImage(IImage) {#addimage}

Add an image to a presentation.

```csharp
public IPPImage AddImage(IImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | IImage | Image to add. |

### Return Value

Added image.

### Remarks

This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation.

### See Also

* interface [IPPImage](../../ippimage)
* interface [IImage](../../iimage)
* interface [IImageCollection](../../iimagecollection)
* namespace [Aspose.Slides](../../iimagecollection)
* assembly [Aspose.Slides](../../../)

---

## AddImage(MemoryStream) {#addimage_5}

Adds image from a memory stream.

```csharp
public IPPImage AddImage(MemoryStream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | MemoryStream | Memory stream. |

### Return Value

Added image.

### See Also

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* namespace [Aspose.Slides](../../iimagecollection)
* assembly [Aspose.Slides](../../../)

---

## AddImage(Stream) {#addimage_6}

Add an image to a presentation from stream.

```csharp
public IPPImage AddImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream to add image from. |

### Return Value

Added image.

### Remarks

This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image.

### See Also

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* namespace [Aspose.Slides](../../iimagecollection)
* assembly [Aspose.Slides](../../../)

---

## AddImage(Stream, LoadingStreamBehavior) {#addimage_7}

Creates and adds an image to a presentation from stream.

```csharp
public IPPImage AddImage(Stream stream, LoadingStreamBehavior loadingStreamBehavior)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream to add image file from. |
| loadingStreamBehavior | LoadingStreamBehavior | The behavior which will be applied to the stream. |

### Return Value

Added [`IPPImage`](../../ippimage).

### See Also

* interface [IPPImage](../../ippimage)
* enum [LoadingStreamBehavior](../../loadingstreambehavior)
* interface [IImageCollection](../../iimagecollection)
* namespace [Aspose.Slides](../../iimagecollection)
* assembly [Aspose.Slides](../../../)

---

## AddImage(byte[]) {#addimage_3}

Adds an image to a presentation from specified buffer.

```csharp
public IPPImage AddImage(byte[] buffer)
```

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | Byte[] | Buffer. |

### Return Value

Added image.

### See Also

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* namespace [Aspose.Slides](../../iimagecollection)
* assembly [Aspose.Slides](../../../)

---

## AddImage(IPPImage) {#addimage_1}

Adds a copy of an image from an another presentation.

```csharp
public IPPImage AddImage(IPPImage imageSource)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | IPPImage | Source image. |

### Return Value

Added image.

### See Also

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* namespace [Aspose.Slides](../../iimagecollection)
* assembly [Aspose.Slides](../../../)

---

## AddImage(ISvgImage) {#addimage_2}

Add an image to a presentation from SVG object.

```csharp
public IPPImage AddImage(ISvgImage svgImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | ISvgImage | SVG image object [`ISvgImage`](../../isvgimage) |

### Return Value

Added image.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when svgImage parameter is null. |

### See Also

* interface [IPPImage](../../ippimage)
* interface [ISvgImage](../../isvgimage)
* interface [IImageCollection](../../iimagecollection)
* namespace [Aspose.Slides](../../iimagecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
