---
title: ThreeDFormat
second_title: Aspose.Sildes for .NET API 参考
description: 表示三维属性。
type: docs
weight: 11180
url: /zh/aspose.slides/threedformat/
---

## ThreeDFormat 类

表示三维属性。

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允许获取基本的 IPresentationComponent 接口。只读 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | 返回或设置底部三维斜角的类型。只读 [`IShapeBevel`](../ishapebevel)。 |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | 返回或设置顶部三维斜角的类型。只读 [`IShapeBevel`](../ishapebevel)。 |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | 返回或设置相机的设置。只读 [`ICamera`](../icamera)。 |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | 返回或设置轮廓的颜色。只读 [`IColorFormat`](../icolorformat)。 |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | 返回或设置三维轮廓的宽度。读写 Double。 |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | 返回或设置三维形状的深度。读写 Double。 |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | 返回或设置挤出的颜色。只读 [`IColorFormat`](../icolorformat)。 |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | 返回或设置挤出效果的高度。读写 Double。 |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | 返回或设置光的类型。只读 [`ILightRig`](../ilightrig)。 |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | 返回或设置材料的类型。读写 [`MaterialPresetType`](../materialpresettype)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 与指定对象进行比较。 |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | 获取有效的三维格式数据，并应用继承。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 返回哈希代码。 |

### 示例

以下示例显示如何在 PowerPoint 演示文稿中添加三维形状。

```csharp
[C#]
// 创建 Presentation 类的实例。
using (Presentation pres = new Presentation())
{
	// 使用 AddAutoShape 方法添加形状
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// 定义 TextFrame 及其属性
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// 定义 ThreeDFormat 属性
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// 保存演示文稿文件
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

以下示例显示如何在 PowerPoint 演示文稿中对三维形状应用渐变效果。

```csharp
[C#]
// 创建 Presentation 类的实例。
using (Presentation pres = new Presentation())
{
	// 使用 AddAutoShape 方法添加形状
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// 定义 TextFrame 及其属性
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// 将 FillFormat.FillType 配置为 FillType.Gradient，并定义渐变属性
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// 定义 ThreeDFormat 属性
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// 保存演示文稿文件
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

以下示例显示如何在文本上应用三维效果。要创建三维文本，可以使用 WordArt 变换效果。

```csharp
[C#]
// 创建 Presentation 类的实例。
using (Presentation pres = new Presentation())
{
	// 使用 AddAutoShape 方法添加形状
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// 定义 TextFrame 及其属性
    shape.TextFrame.Text = "3D Text";
	// 将 FillFormat.FillType 配置为 FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// 配置 TextFrame 的部分并配置 PortionFormat 的属性
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // 设置 "Arch Up" WordArt 变换效果
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// 定义 ITextFrame 的 ThreeDFormat 属性
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// 保存演示文稿文件
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### 另请参阅

* class [PVIObject](../pviobject)
* interface [IThreeDFormat](../ithreedformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->