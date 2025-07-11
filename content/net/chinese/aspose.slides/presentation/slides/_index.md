---
title: Slides
second_title: Aspose.Sildes for .NET API Reference
description: 返回演示文稿中定义的所有幻灯片的列表。 只读 ISlideCollectionaspose.slides/islidecollection。
type: docs
weight: 230
url: /zh/aspose.slides/presentation/slides/
---

## Presentation.Slides 属性

返回演示文稿中定义的所有幻灯片的列表。 只读 [`ISlideCollection`](../../islidecollection)。

```csharp
public ISlideCollection Slides { get; }
```

### 示例

以下示例显示如何设置 PowerPoint 演示文稿幻灯片的背景颜色。

```csharp
[C#]
// 实例化表示演示文档文件的 Presentation 类
using (Presentation pres = new Presentation())
{
    // 将第一张 ISlide 的背景颜色设置为蓝色
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Solid;
    pres.Slides[0].Background.FillFormat.SolidFillColor.Color = Color.Blue;
    pres.Save("ContentBG_out.pptx", SaveFormat.Pptx);
}
```

以下示例显示如何设置 PowerPoint 演示文稿幻灯片的背景图像。

```csharp
[C#]
// 实例化表示演示文档文件的 Presentation 类
using (Presentation pres = new Presentation("SetImageAsBackground.pptx"))
{
    // 使用图像设置背景
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Picture;
    pres.Slides[0].Background.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;
    // 设置图片
    System.Drawing.Image img = (System.Drawing.Image)new Bitmap(dataDir + "Tulips.jpg");
    // 将图像添加到演示文稿图像集合
    IPPImage imgx = pres.Images.AddImage(img);
    pres.Slides[0].Background.FillFormat.PictureFillFormat.Picture.Image = imgx;
    // 将演示文稿写入磁盘
    pres.Save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
}
```

以下示例显示如何为演示文稿添加幻灯片切换。

```csharp
[C#]
// 实例化 Presentation 类以加载源演示文稿文件
using (Presentation presentation = new Presentation("AccessSlides.pptx"))
{
    // 在幻灯片 1 上应用圆形切换
    presentation.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // 在幻灯片 2 上应用组合切换
    presentation.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // 将演示文稿写入磁盘
    presentation.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

以下示例显示如何添加高级幻灯片切换。

```csharp
[C#]
// 实例化表示演示文档文件的 Presentation 类
using (Presentation pres = new Presentation("BetterSlideTransitions.pptx"))
{
    // 在幻灯片 1 上应用圆形切换
    pres.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // 设置切换时间为 3 秒
    pres.Slides[0].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[0].SlideShowTransition.AdvanceAfterTime = 3000;
    // 在幻灯片 2 上应用组合切换
    pres.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // 设置切换时间为 5 秒
    pres.Slides[1].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[1].SlideShowTransition.AdvanceAfterTime = 5000;
    // 在幻灯片 3 上应用缩放切换
    pres.Slides[2].SlideShowTransition.Type = TransitionType.Zoom;
    // 设置切换时间为 7 秒
    pres.Slides[2].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[2].SlideShowTransition.AdvanceAfterTime = 7000;
    // 将演示文稿写入磁盘
    pres.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

### 另请参见

* 接口 [ISlideCollection](../../islidecollection)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->