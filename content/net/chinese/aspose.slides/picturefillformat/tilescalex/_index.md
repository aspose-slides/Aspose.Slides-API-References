---
title: TileScaleX
second_title: Aspose.Sildes for .NET API Reference
description: 返回或设置纹理填充的水平缩放比例（以百分比表示）。可读写单精度浮点数。
type: docs
weight: 160
url: /zh/aspose.slides/picturefillformat/tilescalex/
---

## PictureFillFormat.TileScaleX 属性

返回或设置纹理填充的水平缩放比例（以百分比表示）。可读写单精度浮点数。

```csharp
public float TileScaleX { get; set; }
```

### 示例

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // 获取形状的图片填充格式
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // 将图片填充模式设置为平铺
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // 将纹理的水平缩放设置为120%
    pictureFillFormat.TileScaleX = 120;
}
```

### 另请参见

* class [PictureFillFormat](../../picturefillformat)
* namespace [Aspose.Slides](../../picturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->