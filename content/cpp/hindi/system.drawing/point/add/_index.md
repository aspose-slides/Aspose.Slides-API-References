---
title: Add()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्दिष्ट Size ऑब्जेक्ट की चौड़ाई और ऊँचाई मानों को क्रमशः निर्दिष्ट Point ऑब्जेक्ट के X और Y निर्देशांक मानों में जोड़ता है।
type: docs
weight: 183
url: /hi/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) मेथड

निर्दिष्ट [Size](../../size/) ऑब्जेक्ट की चौड़ाई और ऊँचाई मानों को निर्दिष्ट [Point](../) ऑब्जेक्ट के X और Y निर्देशांक मानों में क्रमशः जोड़ता है।

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| point | const [Point](../)\& | ट्रांसलेट करने हेतु **point** |
| size | const [Size](../../size/)\& | वह [Size](../../size/) ऑब्जेक्ट जो **point** के कोऑर्डिनेट मानों में जोड़ने के लिए मान निर्दिष्ट करता है |

### रिटर्न वैल्यू

एक नया [Point](../) ऑब्जेक्ट जिसका X निर्देशांक मान **point** के X निर्देशांक मान और **size** की चौड़ाई मान के योग के बराबर है और Y निर्देशांक मान **point** के Y निर्देशांक मान और **size** की ऊँचाई मान के योग के बराबर है।

## संबंधित देखें

* क्लास [Point](../)
* क्लास [Size](../../size/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)