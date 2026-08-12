---
title: LockBits()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक Bitmap को सिस्टम मेमोरी में लॉक करता है।
type: docs
weight: 118
url: /hi/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) विधि

एक [Bitmap](../) को सिस्टम मेमोरी में लॉक करता है।

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | एक आयत जो छवि के उस क्षेत्र को निर्दिष्ट करती है जिसे लॉक किया जाना है |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | बिटमैप तक पहुँच स्तर निर्दिष्ट करती है |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | इस बिटमैप का डेटा फ़ॉर्मेट |

### वापसी मान

एक साझा पॉइंटर जो BitmapData ऑब्जेक्ट की ओर इंगित करता है, जिसमें किए गए लॉक ऑपरेशन की जानकारी होती है।

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) विधि

एक [Bitmap](../) को सिस्टम मेमोरी में लॉक करता है।

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | एक आयत जो छवि के उस क्षेत्र को निर्दिष्ट करती है जिसे लॉक किया जाना है |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | बिटमैप तक पहुँच स्तर निर्दिष्ट करती है |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | इस बिटमैप का डेटा फ़ॉर्मेट |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | लॉक ऑपरेशन के बारे में जानकारी रखता है |

### वापसी मान

एक साझा पॉइंटर जो BitmapData ऑब्जेक्ट की ओर इंगित करता है, जिसमें किए गए लॉक ऑपरेशन की जानकारी होती है।

## संबंधित देखें

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)