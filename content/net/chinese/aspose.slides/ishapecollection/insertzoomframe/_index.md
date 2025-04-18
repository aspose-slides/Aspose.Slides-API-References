---
title: InsertZoomFrame
second_title: Aspose.Slides for .NET API 参考
description: 创建一个新的 Zoom 对象并将其插入到指定索引处的集合中
type: docs
weight: 360
url: /zh/aspose.slides/ishapecollection/insertzoomframe/
---
## InsertZoomFrame(int, float, float, float, float, ISlide) {#insertzoomframe}

创建一个新的 Zoom 对象并将其插入到指定索引处的集合中。

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 零-应插入缩放帧的基于索引。 |
| x | Single | 新缩放框的 X 坐标Single。 |
| y | Single | 新缩放框的 Y 坐标Single。 |
| width | Single | 新缩放框的宽度Single。 |
| height | Single | 新缩放框的高度Single。 |
| slide | ISlide | Zoom frame[`ISlide`](../../islide)引用的幻灯片对象。 |

### 返回值

创建缩放对象[`IZoomFrame`](../../izoomframe)。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 引用的幻灯片不属于当前演示文稿。 |

### 例子

此示例演示在集合的指定索引处创建和插入缩放对象 （假设“Presentation.pptx”演示文稿中至少有两张幻灯片）:

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1]);
}
```

### 也可以看看

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IShapeCollection](../../ishapecollection)
* 命名空间 [Aspose.Slides](../../ishapecollection)
* 部件 [Aspose.Slides](../../../)

---

## InsertZoomFrame(int, float, float, float, float, ISlide, IPPImage) {#insertzoomframe_1}

创建一个新的 Zoom 对象并将其插入到指定索引处的集合中。

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide, IPPImage image)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 零-应插入缩放帧的基于索引。 |
| x | Single | 新缩放框的 X 坐标Single。 |
| y | Single | 新缩放框的 Y 坐标Single。 |
| width | Single | 新缩放框的宽度Single。 |
| height | Single | 新缩放框的高度Single。 |
| slide | ISlide | Zoom frame[`ISlide`](../../islide)引用的幻灯片对象。 |
| image | IPPImage | 引用幻灯片的图像[`IPPImage`](../../ippimage) |

### 返回值

创建缩放对象[`IZoomFrame`](../../izoomframe)。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 引用的幻灯片不属于当前演示文稿。 |

### 例子

此示例演示在集合的指定索引处创建和插入缩放对象 （假设“Presentation.pptx”演示文稿中至少有两张幻灯片）:

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1], image);
}
```

### 也可以看看

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IPPImage](../../ippimage)
* interface [IShapeCollection](../../ishapecollection)
* 命名空间 [Aspose.Slides](../../ishapecollection)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
