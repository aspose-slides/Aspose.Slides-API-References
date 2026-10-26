---
title: RectangleF()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया RectangleF ऑब्जेक्ट इंस्टेंस बनाता है जो X और Y निर्देशांक तथा चौड़ाई और ऊँचाई मान 0 पर सेट की गई आयत का प्रतिनिधित्व करता है।
type: docs
weight: 1
url: /hi/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() कंस्ट्रक्टर

[RectangleF](../) ऑब्जेक्ट का नया इंस्टेंस बनाता है जो X और Y निर्देशांक तथा चौड़ाई और ऊँचाई मान 0 पर सेट किए हुए एक आयत का प्रतिनिधित्व करता है।

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) कंस्ट्रक्टर

[RectangleF](../) ऑब्जेक्ट का नया इंस्टेंस बनाता है जो उसके ऊपर बाएँ कोने के निर्दिष्ट निर्देशांक तथा चौड़ाई और ऊँचाई के साथ एक आयत का प्रतिनिधित्व करता है।

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | आयत के ऊपर बाएँ कोने के X निर्देशांक का मान |
| y | **float** | आयत के ऊपर बाएँ कोने के Y निर्देशांक का मान |
| width | **float** | आयत की चौड़ाई |
| height | **float** | आयत की ऊँचाई |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) कंस्ट्रक्टर

[RectangleF](../) ऑब्जेक्ट का नया इंस्टेंस बनाता है जो उसके ऊपर बाएँ कोने के निर्देशांक को [PointF](../../pointf/) क्लास के इंस्टेंस के रूप में और उसकी चौड़ाई व ऊँचाई को [SizeF](../../sizef/) क्लास के इंस्टेंस के रूप में निर्दिष्ट करता है।

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | आयत के ऊपर बाएँ कोने का स्थान निर्दिष्ट करता है |
| size | const [SizeF](../../sizef/)\& | आयत की चौड़ाई और ऊँचाई निर्दिष्ट करता है |

## RectangleF::RectangleF(const Rectangle\&) कंस्ट्रक्टर

[RectangleF](../) ऑब्जेक्ट का नया इंस्टेंस बनाता है जो निर्दिष्ट आयत के बराबर आयत का प्रतिनिधित्व करता है।

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | [Rectangle](../../rectangle/) क्लास का एक इंस्टेंस जो निर्माण किए जा रहे ऑब्जेक्ट द्वारा प्रतिनिधित्व किए जाने वाले आयत की स्थिति और आकार निर्दिष्ट करता है |

## देखें

* क्लास [RectangleF](../)
* क्लास [PointF](../../pointf/)
* क्लास [SizeF](../../sizef/)
* क्लास [Rectangle](../../rectangle/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)