---
title: ThreeDFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: 3-D गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 11490
url: /hi/aspose.slides/threedformat/
---
## ThreeDFormat क्लास

3-D गुणों का प्रतिनिधित्व करता है।

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent)। |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | नीचे की 3D बीवल के प्रकार को प्राप्त या सेट करता है। केवल-पढ़ने योग्य [`IShapeBevel`](../ishapebevel)। |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | ऊपर की 3D बीवल के प्रकार को प्राप्त या सेट करता है। केवल-पढ़ने योग्य [`IShapeBevel`](../ishapebevel)। |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | कैमरे की सेटिंग्स को प्राप्त या सेट करता है। केवल-पढ़ने योग्य [`ICamera`](../icamera)। |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | कंटूर के रंग को प्राप्त या सेट करता है। केवल-पढ़ने योग्य [`IColorFormat`](../icolorformat)। |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | 3D कंटूर की चौड़ाई को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Double। |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | 3D आकार की गहराई को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Double। |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | एक्सट्रूडिंग के रंग को प्राप्त या सेट करता है। केवल-पढ़ने योग्य [`IColorFormat`](../icolorformat)। |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | एक्सट्रूडिंग प्रभाव की ऊँचाई को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Double। |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | प्रकाश के प्रकार को प्राप्त या सेट करता है। केवल-पढ़ने योग्य [`ILightRig`](../ilightrig)। |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | सामग्री के प्रकार को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [`MaterialPresetType`](../materialpresettype)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | उत्तराधिकार लागू होने के साथ प्रभावी 3-D फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### उदाहरण

निम्न उदाहरण दिखाता है कि PowerPoint प्रस्तुतीकरण में 3D आकार कैसे जोड़ें।

```csharp
[C#]
// Presentation क्लास का एक उदाहरण बनाएं।
using (Presentation pres = new Presentation())
{
	// AddAutoShape मेथड का उपयोग करके एक आकार जोड़ें
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// TextFrame और उसकी प्रॉपर्टीज़ परिभाषित करें
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// ThreeDFormat प्रॉपर्टीज़ परिभाषित करें
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Presentation फ़ाइल सहेजें
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

निम्न उदाहरण दिखाता है कि PowerPoint प्रस्तुतीकरण में 3D आकार पर ग्रेडिएंट प्रभाव कैसे लागू करें।

```csharp
[C#]
// Presentation क्लास का एक इंस्टेंस बनाएं।
using (Presentation pres = new Presentation())
{
	// AddAutoShape मेथड का उपयोग करके एक आकार जोड़ें
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// TextFrame और उसकी प्रॉपर्टीज़ परिभाषित करें
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// FillFormat.FillType को FillType.Gradient सेट करें और ग्रेडिएंट प्रॉपर्टीज़ परिभाषित करें
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// ThreeDFormat प्रॉपर्टीज़ परिभाषित करें
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Presentation फ़ाइल सहेजें
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

निम्न उदाहरण दिखाता है कि टेक्स्ट पर 3D प्रभाव कैसे लागू करें। 3D टेक्स्ट बनाने के लिए WordArt ट्रांसफ़ॉर्म प्रभाव का उपयोग करना संभव है।

```csharp
[C#]
// Presentation क्लास का एक इंस्टेंस बनाएं।
using (Presentation pres = new Presentation())
{
	// AddAutoShape मेथड का उपयोग करके एक आकार जोड़ें
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// TextFrame और उसकी प्रॉपर्टीज़ परिभाषित करें
    shape.TextFrame.Text = "3D Text";
	// FillFormat.FillType को FillType.NoFill सेट करें
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// TextFrame के Portion को कॉन्फ़िगर करें और PortionFormat की प्रॉपर्टीज़ सेट करें
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // "Arch Up" WordArt ट्रांसफ़ॉर्म इफ़ेक्ट सेट करें
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// ITextFrame की ThreeDFormat प्रॉपर्टीज़ परिभाषित करें
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Presentation फ़ाइल सहेजें
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### संबंधित देखें

* क्लास [PVIObject](../pviobject)
* इंटरफ़ेस [IThreeDFormat](../ithreedformat)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->