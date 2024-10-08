---
title: Image
second_title: Aspose.Slides for .NET API 参考
description: 获取或设置缩放对象的图像 读/写IPPImageaspose.slides/ippimage
type: docs
weight: 20
url: /zh/aspose.slides/izoomobject/image/
---
## IZoomObject.Image property

获取或设置缩放对象的图像。 读/写[`IPPImage`](../../ippimage)。

```csharp
public IPPImage Image { get; set; }
```

### 例子

该示例演示更改缩放对象的图像:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    zoomFrame.Image = image;
}
```

### 也可以看看

* interface [IPPImage](../../ippimage)
* interface [IZoomObject](../../izoomobject)
* 命名空间 [Aspose.Slides](../../izoomobject)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
