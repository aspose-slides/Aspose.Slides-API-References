---
title: ThreeDFormat
second_title: Aspose.Sildes .NET API 參考
description: 代表 3-D 屬性。
type: docs
weight: 11490
url: /zh-hant/aspose.slides/threedformat/
---
## ThreeDFormat 類別

代表 3-D 屬性。

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允許取得基礎 IPresentationComponent 介面。唯讀 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | 傳回或設定底部 3D 斜面類型。唯讀 [`IShapeBevel`](../ishapebevel)。 |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | 傳回或設定頂部 3D 斜面類型。唯讀 [`IShapeBevel`](../ishapebevel)。 |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | 傳回或設定相機設定。唯讀 [`ICamera`](../icamera)。 |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | 傳回或設定輪廓顏色。唯讀 [`IColorFormat`](../icolorformat)。 |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | 傳回或設定 3D 輪廓寬度。可讀寫 Double。 |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | 傳回或設定 3D 形狀深度。可讀寫 Double。 |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | 傳回或設定擠壓顏色。唯讀 [`IColorFormat`](../icolorformat)。 |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | 傳回或設定擠壓效果高度。可讀寫 Double。 |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | 傳回或設定光源類型。唯讀 [`ILightRig`](../ilightrig)。 |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | 傳回或設定材質類型。可讀寫 [`MaterialPresetType`](../materialpresettype)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 與指定的物件比較。 |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | 取得套用繼承後的有效 3-D 格式化資料。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 傳回雜湊碼。 |

### 範例

以下範例說明如何在 PowerPoint 簡報中新增 3D 形狀。

```csharp
[C#]
// 建立 Presentation 類別的實例。
using (Presentation pres = new Presentation())
{
	// 使用 AddAutoShape 方法新增形狀
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// 定義 TextFrame 及其屬性
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// 定義 ThreeDFormat 屬性
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// 儲存 Presentation 檔案
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

以下範例說明如何對 PowerPoint 簡報中的 3D 形狀套用漸層效果。

```csharp
[C#]
// 建立 Presentation 類別的實例.
using (Presentation pres = new Presentation())
{
	// 使用 AddAutoShape 方法新增形狀
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// 定義 TextFrame 及其屬性
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// 將 FillFormat.FillType 設定為 FillType.Gradient 並定義漸層屬性
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// 定義 ThreeDFormat 屬性
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// 儲存 Presentation 檔案
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

以下範例說明如何對文字套用 3D 效果。若要建立 3D 文字，可使用 WordArt 變形效果。

```csharp
[C#]
// 建立 Presentation 類別的實例。
using (Presentation pres = new Presentation())
{
	// 使用 AddAutoShape 方法新增形狀
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// 定義 TextFrame 及其屬性
    shape.TextFrame.Text = "3D Text";
	// 將 FillFormat.FillType 設定為 FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// 設定 TextFrame 的 Portion 並設定 PortionFormat 的屬性
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // 設定「Arch Up」WordArt 變形效果
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// 定義 ITextFrame 的 ThreeDFormat 屬性
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// 儲存 Presentation 檔案
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### 另請參閱

* 類別 [PVIObject](../pviobject)
* 介面 [IThreeDFormat](../ithreedformat)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->