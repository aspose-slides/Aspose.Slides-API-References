---
title: ThreeDFormat
second_title: Aspose.Sildes for .NET API リファレンス
description: 3-D プロパティを表します。
type: docs
weight: 11490
url: /ja/aspose.slides/threedformat/
---
## ThreeDFormat クラス

3-D プロパティを表します。

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | ベースの IPresentationComponent インターフェイスを取得できます。読み取り専用 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | 底部の 3D ベベルのタイプを取得または設定します。読み取り専用 [`IShapeBevel`](../ishapebevel)。 |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | 上部の 3D ベベルのタイプを取得または設定します。読み取り専用 [`IShapeBevel`](../ishapebevel)。 |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | カメラの設定を取得または設定します。読み取り専用 [`ICamera`](../icamera)。 |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | 輪郭の色を取得または設定します。読み取り専用 [`IColorFormat`](../icolorformat)。 |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | 3D 輪郭の幅を取得または設定します。読み書き Double。 |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | 3D シェイプの深さを取得または設定します。読み書き Double。 |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | 押し出しの色を取得または設定します。読み取り専用 [`IColorFormat`](../icolorformat)。 |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | 押し出し効果の高さを取得または設定します。読み書き Double。 |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | ライトのタイプを取得または設定します。読み取り専用 [`ILightRig`](../ilightrig)。 |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | マテリアルのタイプを取得または設定します。読み書き [`MaterialPresetType`](../materialpresettype)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 指定されたオブジェクトと比較します。 |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | 継承が適用された有効な 3-D 書式設定データを取得します。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ハッシュコードを返します。 |

### 例

以下の例は、PowerPoint プレゼンテーションに 3D シェイプを追加する方法を示しています。

```csharp
[C#]
// Presentation クラスのインスタンスを作成します。
using (Presentation pres = new Presentation())
{
	// AddAutoShape メソッドを使用してシェイプを追加します。
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// TextFrame とそのプロパティを定義します。
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// ThreeDFormat プロパティを定義します。
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Presentation ファイルを保存します。
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

以下の例は、PowerPoint プレゼンテーションの 3D シェイプにグラデーション効果を適用する方法を示しています。

```csharp
[C#]
// Presentation クラスのインスタンスを作成します。
using (Presentation pres = new Presentation())
{
	// AddAutoShape メソッドを使用してシェイプを追加します。
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// TextFrame とそのプロパティを定義します。
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// FillFormat.FillType を FillType.Gradient に設定し、グラデーションのプロパティを定義します。
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// ThreeDFormat プロパティを定義します。
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Presentation ファイルを保存します。
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

以下の例は、テキストに 3D 効果を適用する方法を示しています。3D テキストを作成するには、WordArt の変形効果を使用できます。

```csharp
[C#]
// Presentation クラスのインスタンスを作成します。
using (Presentation pres = new Presentation())
{
	// AddAutoShape メソッドを使用してシェイプを追加します。
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// TextFrame とそのプロパティを定義します。
    shape.TextFrame.Text = "3D Text";
	// FillFormat.FillType を FillType.NoFill に設定します。
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// TextFrame の Portion を設定し、PortionFormat のプロパティを設定します。
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // "Arch Up" WordArt 変形効果を設定します。
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// ITextFrame の ThreeDFormat プロパティを定義します。
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Presentation ファイルを保存します。
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### 関連項目

* クラス [PVIObject](../pviobject)
* インターフェイス [IThreeDFormat](../ithreedformat)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->