---
title: GetImage
second_title: Aspose.Slides for .NET API 参考
description: 返回一个带有自定义缩放的缩略图像对象。
type: docs
weight: 80
url: /zh/aspose.slides/slide/getimage/
---

## GetImage(float, float) {#getimage_5}

返回一个带有自定义缩放的缩略图像对象。

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | Single | 缩放该缩略图在 x 轴方向的值。 |
| scaleY | Single | 缩放该缩略图在 y 轴方向的值。 |

### 返回值

IImage 对象。

### 示例

以下示例演示如何从 PowerPoint 演示文稿生成缩略图。

```csharp
[C#]
// 实例化表示演示文稿文件的 Presentation 类
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // 访问第一张幻灯片
    ISlide sld = pres.Slides[0];
    // 创建全尺寸图像
    IImage bmp = sld.GetImage(1f, 1f);
    // 以 JPEG 格式将图像保存到磁盘
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

以下示例演示如何将幻灯片转换为位图并将图像保存为 PNG。

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // 将演示文稿中的第一张幻灯片转换为具有指定大小的位图对象
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // 以 PNG 格式保存图像
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

以下示例演示如何将 PowerPoint PPT/PPTX 转换为 JPG。

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// 创建全尺寸图像
		IImage bmp = sld.GetImage(1f, 1f);
		// 以 JPEG 格式将图像保存到磁盘
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

以下示例演示如何将 PowerPoint PPT/PPTX 转换为带自定义尺寸的 JPG。

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// 定义尺寸
	int desiredX = 1200;
	int desiredY = 800;
	// 获取 X 和 Y 的缩放值
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// 创建全尺寸图像
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// 以 JPEG 格式将图像保存到磁盘
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### 另请参见

* 接口 [IImage](../../iimage)
* 类 [Slide](../../slide)
* 命名空间 [Aspose.Slides](../../slide)
* 程序集 [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

返回一个缩略图像对象（实际大小的 20%）。

```csharp
public IImage GetImage()
```

### 另请参见

* 接口 [IImage](../../iimage)
* 类 [Slide](../../slide)
* 命名空间 [Aspose.Slides](../../slide)
* 程序集 [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

返回一个具有指定尺寸的缩略图像对象。

```csharp
public IImage GetImage(Size imageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageSize | Size | 要创建的图像的大小。 |

### 返回值

图像对象。

### 示例

以下示例演示如何使用 C# 将幻灯片转换为具有自定义尺寸的图像。

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // 将演示文稿中的第一张幻灯片转换为具有指定大小的位图
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // 以 JPEG 格式保存图像
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### 另请参见

* 接口 [IImage](../../iimage)
* 类 [Slide](../../slide)
* 命名空间 [Aspose.Slides](../../slide)
* 程序集 [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

返回一个具有指定参数的缩略 tiff 图像对象。

```csharp
public IImage GetImage(ITiffOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | ITiffOptions | Tiff 选项。 |

### 返回值

图像对象。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 当 options.SlideLayoutOption 是 NotesCommentsLayoutingOptions 且其属性 NotesPosition 取值为 NotesPositions.BottomFull 时引发。 |

### 另请参见

* 接口 [IImage](../../iimage)
* 接口 [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* 类 [Slide](../../slide)
* 命名空间 [Aspose.Slides](../../slide)
* 程序集 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

返回一个缩略图像对象。

```csharp
public IImage GetImage(IRenderingOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | IRenderingOptions | 渲染选项。 |

### 返回值

图像对象。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 当 notesCommentsLayouting.NotesPosition 取值为 NotesPositions.BottomFull 时引发。 |

### 另请参见

* 接口 [IImage](../../iimage)
* 接口 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 类 [Slide](../../slide)
* 命名空间 [Aspose.Slides](../../slide)
* 程序集 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

返回一个带有自定义缩放的缩略图像对象。

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | IRenderingOptions | 渲染选项。 |
| scaleX | Single | 缩放该缩略图在 x 轴方向的值。 |
| scaleY | Single | 缩放该缩略图在 y 轴方向的值。 |

### 返回值

位图对象。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 当 notesCommentsLayouting.NotesPosition 取值为 NotesPositions.BottomFull 时引发。 |

### 示例

以下示例演示如何使用 C# 将带有注释和评论的幻灯片转换为图像。

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // 创建渲染选项
    IRenderingOptions options = new RenderingOptions();
    // 创建注释布局选项
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // 设置注释在页面上的位置
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // 设置评论在页面上的位置
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // 设置评论输出区域的宽度
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // 设置评论区域的颜色
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // 设置渲染的布局选项
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // 将演示文稿的第一张幻灯片转换为 IImage 对象
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // 以 GIF 格式保存图像
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### 另请参见

* 接口 [IImage](../../iimage)
* 接口 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 类 [Slide](../../slide)
* 命名空间 [Aspose.Slides](../../slide)
* 程序集 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

返回一个具有指定尺寸的缩略图像对象。

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | IRenderingOptions | 渲染选项。 |
| imageSize | Size | 要创建的图像的大小。 |

### 返回值

图像对象。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 当 options.SlideLayoutOption 是 NotesCommentsLayoutingOptions 且其属性 NotesPosition 取值为 NotesPositions.BottomFull 时引发。 |

### 另请参见

* 接口 [IImage](../../iimage)
* 接口 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 类 [Slide](../../slide)
* 命名空间 [Aspose.Slides](../../slide)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->