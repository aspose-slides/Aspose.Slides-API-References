---
title: ThreeDFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu thị các thuộc tính 3-D.
type: docs
weight: 11510
url: /vi/aspose.slides/threedformat/
---
## ThreeDFormat lớp

Represents 3-D properties.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ bản. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Trả về hoặc đặt loại góc cạnh 3D phía dưới. Chỉ đọc [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Trả về hoặc đặt loại góc cạnh 3D phía trên. Chỉ đọc [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Trả về hoặc đặt cài đặt của máy ảnh. Chỉ đọc [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Trả về hoặc đặt màu của đường viền. Chỉ đọc [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Trả về hoặc đặt độ rộng của đường viền 3D. Đọc/ghi Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Trả về hoặc đặt độ sâu của hình dạng 3D. Đọc/ghi Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Trả về hoặc đặt màu của đùn. Chỉ đọc [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Trả về hoặc đặt chiều cao của hiệu ứng đùn. Đọc/ghi Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Trả về hoặc đặt loại ánh sáng. Chỉ đọc [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Trả về hoặc đặt loại vật liệu. Đọc/ghi [`MaterialPresetType`](../materialpresettype). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng được chỉ định. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Lấy dữ liệu định dạng 3-D hiệu quả với kế thừa được áp dụng. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Ví dụ

Ví dụ sau đây cho thấy cách thêm hình dạng 3D trong bản trình bày PowerPoint.

```csharp
[C#]
// Tạo một thể hiện của lớp Presentation class.
using (Presentation pres = new Presentation())
{
	// Thêm một hình dạng bằng phương pháp AddAutoShape method
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Định nghĩa TextFrame và các thuộc tính của nó
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Định nghĩa các thuộc tính ThreeDFormat Properties
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Lưu tệp Presentation file
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Ví dụ sau đây cho thấy cách áp dụng hiệu ứng Gradient lên hình dạng 3D trong bản trình bày PowerPoint.

```csharp
[C#]
// Tạo một thể hiện của lớp Presentation class.
using (Presentation pres = new Presentation())
{
	// Thêm một hình dạng bằng phương pháp AddAutoShape method
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Định nghĩa TextFrame và các thuộc tính của nó
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Cấu hình FillFormat.FillType là FillType.Gradient và định nghĩa các thuộc tính gradient
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Định nghĩa các thuộc tính ThreeDFormat Properties
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Lưu tệp Presentation file
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Ví dụ sau đây cho thấy cách áp dụng hiệu ứng 3D lên văn bản. Để tạo văn bản 3D có thể sử dụng hiệu ứng biến đổi WordArt.

```csharp
[C#]
// Tạo một thể hiện của lớp Presentation class.
using (Presentation pres = new Presentation())
{
	// Thêm một hình dạng bằng phương pháp AddAutoShape method
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Định nghĩa TextFrame và các thuộc tính của nó
    shape.TextFrame.Text = "3D Text";
	// Cấu hình FillFormat.FillType là FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Cấu hình Portion của TextFrame và cấu hình các thuộc tính của PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // thiết lập hiệu ứng biến đổi WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Định nghĩa các thuộc tính ThreeDFormat của ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Lưu tệp Presentation file
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Xem Thêm

* lớp [PVIObject](../pviobject)
* giao diện [IThreeDFormat](../ithreedformat)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->