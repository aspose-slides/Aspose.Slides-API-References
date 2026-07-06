---
title: ThreeDFormat
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 3-D 속성을 나타냅니다.
type: docs
weight: 11490
url: /ko/aspose.slides/threedformat/
---
## ThreeDFormat 클래스

3-D 속성을 나타냅니다.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 기본 IPresentationComponent 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | 하단 3D 베벨의 유형을 반환하거나 설정합니다. 읽기 전용 [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | 상단 3D 베벨의 유형을 반환하거나 설정합니다. 읽기 전용 [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | 카메라 설정을 반환하거나 설정합니다. 읽기 전용 [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | 윤곽의 색상을 반환하거나 설정합니다. 읽기 전용 [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | 3D 윤곽의 너비를 반환하거나 설정합니다. 읽기/쓰기 Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | 3D 형태의 깊이를 반환하거나 설정합니다. 읽기/쓰기 Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | 압출의 색상을 반환하거나 설정합니다. 읽기 전용 [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | 압출 효과의 높이를 반환하거나 설정합니다. 읽기/쓰기 Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | 조명의 유형을 반환하거나 설정합니다. 읽기 전용 [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | 재료의 유형을 반환하거나 설정합니다. 읽기/쓰기 [`MaterialPresetType`](../materialpresettype). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 지정된 객체와 비교합니다. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | 상속이 적용된 효과적인 3-D 서식 데이터를 가져옵니다. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 해시 코드를 반환합니다. |

### 예제

다음 예제는 PowerPoint 프레젠테이션에 3D 도형을 추가하는 방법을 보여줍니다.

```csharp
[C#]
// Presentation 클래스의 인스턴스를 생성합니다.
using (Presentation pres = new Presentation())
{
	// AddAutoShape 메서드를 사용하여 도형을 추가합니다.
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// TextFrame 및 해당 속성을 정의합니다.
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// ThreeDFormat 속성을 정의합니다.
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Presentation 파일을 저장합니다.
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

다음 예제는 PowerPoint 프레젠테이션에 3D 도형에 그라디언트 효과를 적용하는 방법을 보여줍니다.

```csharp
[C#]
// Presentation 클래스의 인스턴스를 생성합니다.
using (Presentation pres = new Presentation())
{
	// AddAutoShape 메서드를 사용하여 도형을 추가합니다.
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// TextFrame 및 해당 속성을 정의합니다.
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// FillFormat.FillType을 FillType.Gradient로 설정하고 그라디언트 속성을 정의합니다.
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// ThreeDFormat 속성을 정의합니다.
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Presentation 파일을 저장합니다.
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

다음 예제는 텍스트에 3D 효과를 적용하는 방법을 보여줍니다. 3D 텍스트를 만들기 위해 WordArt 변환 효과를 사용할 수 있습니다.

```csharp
[C#]
// Presentation 클래스의 인스턴스를 생성합니다.
using (Presentation pres = new Presentation())
{
	// AddAutoShape 메서드를 사용하여 도형을 추가합니다.
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// TextFrame 및 해당 속성을 정의합니다.
    shape.TextFrame.Text = "3D Text";
	// FillFormat.FillType을 FillType.NoFill로 설정합니다.
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// TextFrame의 Portion을 구성하고 PortionFormat 속성을 설정합니다.
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // "Arch Up" WordArt 변환 효과를 설정합니다.
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// ITextFrame의 ThreeDFormat 속성을 정의합니다.
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Presentation 파일을 저장합니다.
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### 참고

* 클래스 [PVIObject](../pviobject)
* 인터페이스 [IThreeDFormat](../ithreedformat)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->