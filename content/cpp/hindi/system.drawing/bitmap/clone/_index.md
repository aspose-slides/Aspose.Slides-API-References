---
title: Clone()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: वर्तमान ऑब्जेक्ट की एक प्रति बनाता है।
type: docs
weight: 183
url: /hi/system.drawing/bitmap/clone/
---
## Bitmap::Clone() विधि

वर्तमान ऑब्जेक्ट की एक प्रति बनाता है।

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### रिटर्न मान

वर्तमान ऑब्जेक्ट की एक प्रति।

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए बिटमैप इमेज के एक क्षेत्र की प्रति दर्शाने वाले [Bitmap](../) ऑब्जेक्ट को बनाता है।

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | वह आयत जो कॉपी करने वाले क्षेत्र को निर्दिष्ट करती है |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | नए [Bitmap](../) के लिए पिक्सेल फॉर्मेट |

### रिटर्न मान

निर्मित [Bitmap](../) ऑब्जेक्ट

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए बिटमैप इमेज के एक क्षेत्र की प्रति दर्शाने वाले [Bitmap](../) ऑब्जेक्ट को बनाता है।

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | वह आयत जो कॉपी करने वाले क्षेत्र को निर्दिष्ट करती है |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | नए [Bitmap](../) के लिए पिक्सेल फॉर्मेट |

### रिटर्न मान

निर्मित [Bitmap](../) ऑब्जेक्ट

## देखें

* एनम [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Image](../../image/)
* क्लास [Bitmap](../)
* क्लास [Rectangle](../../rectangle/)
* क्लास [RectangleF](../../rectanglef/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)