---
title: DrawCurve()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: निर्दिष्ट पेन का उपयोग करके एक स्प्लाइन बनाता है।
type: docs
weight: 794
url: /hi/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) method

निर्दिष्ट पेन का उपयोग करके एक स्प्लाइन बनाता है।

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | स्प्लाइन बनाते समय उपयोग करने हेतु पेन |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) बिंदुओं का जो स्प्लाइन को निर्धारित करता है |
| tension | **float** | स्प्लाइन के तनाव को निर्दिष्ट करने वाला मान |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) method

निर्दिष्ट पेन का उपयोग करके एक स्प्लाइन बनाता है।

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | स्प्लाइन बनाते समय उपयोग करने हेतु पेन |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) बिंदुओं का जो स्प्लाइन को निर्धारित करता है |
| tension | **float** | स्प्लाइन के तनाव को निर्दिष्ट करने वाला मान |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) method

निर्दिष्ट पेन का उपयोग करके एक स्प्लाइन बनाता है।

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | स्प्लाइन बनाते समय उपयोग करने हेतु पेन |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) बिंदुओं का जो स्प्लाइन को निर्धारित करता है |
| offset | **int32_t** | **points** ऐरे के पहले तत्व से ऑफ़सेट |
| numberOfSegments | **int32_t** | वक्र में शामिल करने के लिए सेगमेंट की संख्या |
| tension | **float** | स्प्लाइन के तनाव को निर्दिष्ट करने वाला मान |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) method

निर्दिष्ट पेन का उपयोग करके एक स्प्लाइन बनाता है।

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | स्प्लाइन बनाते समय उपयोग करने हेतु पेन |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) बिंदुओं का जो स्प्लाइन को निर्धारित करता है |
| offset | **int32_t** | **points** ऐरे के पहले तत्व से ऑफ़सेट |
| numberOfSegments | **int32_t** | वक्र में शामिल करने के लिए सेगमेंट की संख्या |
| tension | **float** | स्प्लाइन के तनाव को निर्दिष्ट करने वाला मान |

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Pen](../../pen/)
* क्लास [Point](../../point/)
* क्लास [Graphics](../)
* क्लास [PointF](../../pointf/)
* नामस्थान [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)