---
title: SetClip()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: वर्तमान Graphics ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए ड्रॉइंग सतह के क्लिपिंग क्षेत्र को उस निर्दिष्ट ऑपरेशन के परिणाम में सेट करता है जो वर्तमान क्लिप क्षेत्र और निर्दिष्ट क्षेत्र को संयोजित करता है।
type: docs
weight: 690
url: /hi/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) विधि

वर्तमान [Graphics](../) ऑब्जेक्ट द्वारा दर्शाए गए ड्रॉइंग सतह के क्लिपिंग क्षेत्र को उन निर्दिष्ट ऑपरेशन के परिणाम के अनुसार सेट करता है जो वर्तमान क्लिप क्षेत्र और निर्दिष्ट क्षेत्र को संयोजित करता है।

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | संयोजन के लिये एक क्षेत्र निर्दिष्ट करता है |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | संयोजन ऑपरेशन निर्दिष्ट करता है |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) विधि

वर्तमान [Graphics](../) ऑब्जेक्ट द्वारा दर्शाए गए ड्रॉइंग सतह के क्लिपिंग क्षेत्र को उन निर्दिष्ट ऑपरेशन के परिणाम के अनुसार सेट करता है जो वर्तमान क्लिप क्षेत्र और निर्दिष्ट क्षेत्र को संयोजित करता है।

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | संयोजन के लिये एक क्षेत्र निर्दिष्ट करता है |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | संयोजन ऑपरेशन निर्दिष्ट करता है |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) विधि

वर्तमान [Graphics](../) ऑब्जेक्ट द्वारा दर्शाए गए ड्रॉइंग सतह के क्लिपिंग क्षेत्र को उन निर्दिष्ट ऑपरेशन के परिणाम के अनुसार सेट करता है जो वर्तमान क्लिप क्षेत्र और निर्दिष्ट क्षेत्र को संयोजित करता है।

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | संयोजन के लिये एक क्षेत्र निर्दिष्ट करता है |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | संयोजन ऑपरेशन निर्दिष्ट करता है |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) विधि

अभी लागू नहीं किया गया है।

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) विधि

वर्तमान [Graphics](../) ऑब्जेक्ट द्वारा दर्शाए गए ड्रॉइंग सतह के क्लिपिंग क्षेत्र को उस निर्दिष्ट ऑपरेशन के परिणाम के अनुसार सेट करता है जो वर्तमान क्लिप क्षेत्र और ग्राफ़िक्स पाथ द्वारा निर्दिष्ट क्षेत्र को संयोजित करता है।

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | संयोजन के लिये एक क्षेत्र निर्दिष्ट करता है |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | संयोजन ऑपरेशन निर्दिष्ट करता है |

## देखें

* एन्यूम [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Region](../../region/)
* क्लास [Graphics](../)
* क्लास [Rectangle](../../rectangle/)
* क्लास [RectangleF](../../rectanglef/)
* क्लास [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)