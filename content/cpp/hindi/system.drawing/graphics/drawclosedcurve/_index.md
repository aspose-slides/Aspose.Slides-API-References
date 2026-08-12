---
title: DrawClosedCurve()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट पेन का उपयोग करके एक बंद स्प्लाइन बनाता है।
type: docs
weight: 781
url: /hi/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) विधि

निर्दिष्ट pen का उपयोग करके एक बंद spline बनाता है।

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### पर्युक्तियाँ

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | एक pen जिसका उपयोग spline बनाने के लिए किया जाता है |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) बिंदुओं का जो सpline को निर्धारित करता है |
| tension | **float** | spline की tension को निर्धारित करने वाला मान |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | अवहेलित |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) विधि

निर्दिष्ट pen का उपयोग करके एक बंद spline बनाता है।

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### पर्युक्तियाँ

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | एक pen जिसका उपयोग spline बनाने के लिए किया जाता है |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) बिंदुओं का जो सpline को निर्धारित करता है |
| tension | **float** | spline की tension को निर्धारित करने वाला मान |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | अवहेलित |

## संबंधित देखें

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)