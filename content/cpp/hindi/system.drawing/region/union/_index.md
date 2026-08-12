---
title: Union()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा निरूपित क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के यूनियन संचालन के परिणाम से प्रतिस्थापित करता है।
type: docs
weight: 53
url: /hi/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के यूनियन ऑपरेशन के परिणाम से प्रतिस्थापित करता है।

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | एक आयत जो इस क्षेत्र को मिलाने वाले क्षेत्र को परिभाषित करती है |

## Region::Union(const Rectangle\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के यूनियन के परिणाम से प्रतिस्थापित करता है।

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | एक आयत जो इस क्षेत्र को मिलाने वाले क्षेत्र को परिभाषित करती है |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट पथ द्वारा परिभाषित क्षेत्र के यूनियन के परिणाम से प्रतिस्थापित करता है।

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | एक पथ जो इस क्षेत्र को मिलाने वाले क्षेत्र को परिभाषित करता है |

## Region::Union(const SharedPtr\<Region\>\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट क्षेत्र के यूनियन के परिणाम से प्रतिस्थापित करता है।

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | एक क्षेत्र जो इस क्षेत्र को मिलाने के लिए है |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [RectangleF](../../rectanglef/)
* क्लास [Region](../)
* क्लास [Rectangle](../../rectangle/)
* क्लास [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)