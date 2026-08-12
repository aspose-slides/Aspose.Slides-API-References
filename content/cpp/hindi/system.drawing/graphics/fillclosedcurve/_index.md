---
title: FillClosedCurve()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट ब्रश का उपयोग करके बंद स्प्लाइन को ड्रॉ करता है।
type: docs
weight: 807
url: /hi/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) मेथड

निर्दिष्ट ब्रश का उपयोग करके बंद स्प्लाइन को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | स्प्लाइन को ड्रॉ करने के लिए उपयोग किया जाने वाला ब्रश |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) बिंदुओं का जो स्प्लाइन निर्धारित करता है |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | स्प्लाइन की तनाव को निर्दिष्ट करने वाला मान |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) मेथड

निर्दिष्ट ब्रश का उपयोग करके बंद स्प्लाइन को ड्रॉ करता है।

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | स्प्लाइन को ड्रॉ करने के लिए उपयोग किया जाने वाला ब्रश |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) बिंदुओं का जो स्प्लाइन निर्धारित करता है |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | स्प्लाइन की तनाव को निर्दिष्ट करने वाला मान |

## संबंधित देखें

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [Graphics](../)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)