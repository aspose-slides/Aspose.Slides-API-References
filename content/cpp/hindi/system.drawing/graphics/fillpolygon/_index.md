---
title: FillPolygon()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट बहुभुज के आंतरिक भाग को निर्दिष्ट ब्रश का उपयोग करके भरता है।
type: docs
weight: 417
url: /hi/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) विधि

निर्दिष्ट बहुभुज के आंतरिक भाग को निर्दिष्ट ब्रश का उपयोग करके भरता है।

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object that specifies the parameters of the fill |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | An array containing the points that define the polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | The fill mode |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) विधि

निर्दिष्ट बहुभुज के आंतरिक भाग को निर्दिष्ट ब्रश का उपयोग करके भरता है।

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object that specifies the parameters of the fill |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | An array containing the points that define the polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | The fill mode |

## संबंधित देखें

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [Brush](../../brush/)
* क्लास [Point](../../point/)
* क्लास [Graphics](../)
* क्लास [PointF](../../pointf/)
* नेमस्पेस [System::Drawing](../../)
* Library [Aspose.Slides](../../../)