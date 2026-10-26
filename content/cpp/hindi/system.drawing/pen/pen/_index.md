---
title: Pen()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्मित करता है एक नया Pen ऑब्जेक्ट जो निर्दिष्ट रंग को दर्शाता है।
type: docs
weight: 1
url: /hi/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) कंस्ट्रक्टर

निर्मित करता है एक नया [Pen](../) ऑब्जेक्ट जो निर्दिष्ट रंग को दर्शाता है।

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | const [Color](../../color/)\& | The color of the pen represented by the object being constructed |

## Pen::Pen(const Color\&, float) कंस्ट्रक्टर

निर्मित करता है एक नया [Pen](../) ऑब्जेक्ट जो निर्दिष्ट रंग और चौड़ाई को दर्शाता है।

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | const [Color](../../color/)\& | The color of the pen represented by the object being constructed |
| width | **float** | The width of the pen represented by the object being constructed |

## Pen::Pen(const SharedPtr\<Brush\>\&) कंस्ट्रक्टर

निर्मित करता है एक नया [Pen](../) ऑब्जेक्ट और उसे निर्दिष्ट [Brush](../../brush/) ऑब्जेक्ट से आरंभ करता है।

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | The [Brush](../../brush/) object that specifies the fill properties of the pen represented by the object being constructed |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) कंस्ट्रक्टर

निर्मित करता है एक नया [Pen](../) ऑब्जेक्ट और उसे निर्दिष्ट [Brush](../../brush/) ऑब्जेक्ट से आरंभ करता है।

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | The [Brush](../../brush/) object that specifies the fill properties of the pen represented by the object being constructed |
| width | **float** | The width of the pen represented by the object being constructed |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Color](../../color/)
* क्लास [Pen](../)
* क्लास [Brush](../../brush/)
* नेमस्पेस [System::Drawing](../../)
* Library [Aspose.Slides](../../../)