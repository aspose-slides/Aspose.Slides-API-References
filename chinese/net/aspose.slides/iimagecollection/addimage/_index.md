---
title: AddImage
second_title: Aspose.Slides for .NET API 参考
description: 将图像添加到演示文稿
type: docs
weight: 20
url: /zh/net/aspose.slides/iimagecollection/addimage/
---
## AddImage(Image) {#addimage_3}

将图像添加到演示文稿。

```csharp
public IPPImage AddImage(Image image)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Image | 要添加的图像。 |

### 返回值

添加图像。

### 评论

此方法在插入演示文稿之前将 WMF/EMF 图元文件转换为光栅 PNG 图像。

### 也可以看看

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* 命名空间 [Aspose.Slides](../../iimagecollection)
* 部件 [Aspose.Slides](../../../)

---

## AddImage(MemoryStream) {#addimage_4}

从内存流中添加图像。

```csharp
public IPPImage AddImage(MemoryStream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | MemoryStream | 内存流。 |

### 返回值

添加图像。

### 也可以看看

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* 命名空间 [Aspose.Slides](../../iimagecollection)
* 部件 [Aspose.Slides](../../../)

---

## AddImage(Stream) {#addimage_5}

将图像从流中添加到演示文稿。

```csharp
public IPPImage AddImage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要从中添加图像的流。 |

### 返回值

添加图像。

### 评论

此方法可以将 WMF/EMF 图元文件添加到演示文稿中，而无需将它们转换为光栅 PNG 图像。

### 也可以看看

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* 命名空间 [Aspose.Slides](../../iimagecollection)
* 部件 [Aspose.Slides](../../../)

---

## AddImage(Stream, LoadingStreamBehavior) {#addimage_6}

从流中创建图像并将其添加到演示文稿。

```csharp
public IPPImage AddImage(Stream stream, LoadingStreamBehavior loadingStreamBehavior)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要从中添加图像文件的流。 |
| loadingStreamBehavior | LoadingStreamBehavior | 将应用于流的行为。 |

### 返回值

添加[`IPPImage`](../../ippimage)。

### 也可以看看

* interface [IPPImage](../../ippimage)
* enum [LoadingStreamBehavior](../../loadingstreambehavior)
* interface [IImageCollection](../../iimagecollection)
* 命名空间 [Aspose.Slides](../../iimagecollection)
* 部件 [Aspose.Slides](../../../)

---

## AddImage(byte[]) {#addimage_2}

将图像从指定缓冲区添加到演示文稿。

```csharp
public IPPImage AddImage(byte[] buffer)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| buffer | Byte[] | 缓冲区。 |

### 返回值

添加图像。

### 也可以看看

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* 命名空间 [Aspose.Slides](../../iimagecollection)
* 部件 [Aspose.Slides](../../../)

---

## AddImage(IPPImage) {#addimage}

添加来自另一个演示文稿的图像的副本。

```csharp
public IPPImage AddImage(IPPImage imageSource)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageSource | IPPImage | 源图像。 |

### 返回值

添加图像。

### 也可以看看

* interface [IPPImage](../../ippimage)
* interface [IImageCollection](../../iimagecollection)
* 命名空间 [Aspose.Slides](../../iimagecollection)
* 部件 [Aspose.Slides](../../../)

---

## AddImage(ISvgImage) {#addimage_1}

将图像从 SVG 对象添加到演示文稿。

```csharp
public IPPImage AddImage(ISvgImage svgImage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | ISvgImage | SVG 图像对象[`ISvgImage`](../../isvgimage) |

### 返回值

添加图像。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 当 svgImage 参数为空时抛出。 |

### 也可以看看

* interface [IPPImage](../../ippimage)
* interface [ISvgImage](../../isvgimage)
* interface [IImageCollection](../../iimagecollection)
* 命名空间 [Aspose.Slides](../../iimagecollection)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->