---
title: ToString()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट बाइट ऐरे के सभी मानों को उनके हेक्साडेसिमल स्ट्रिंग प्रतिनिधित्व में बदलता है। हेक्साडेसिमल नोटेशन में उपयोग किए जाने वाले अक्षरों का केस और पड़ोसी बाइट्स की प्रत्येक जोड़ी के बीच डाला गया विभाजक संबंधित तर्कों द्वारा निर्दिष्ट किया जाता है।
type: docs
weight: 157
url: /hi/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) विधि

निर्दिष्ट बाइट ऐरे के सभी मानों को उनके हेक्साडेसिमल स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। हेक्साडेसिमल नोटेशन में उपयोग किए जाने वाले अक्षरों का केस और पड़ोसी बाइट्स की प्रत्येक जोड़ी के बीच डाला गया विभाजक संबंधित तर्कों द्वारा निर्दिष्ट किया जाता है।

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जो बाइट्स को परिवर्तित करने के लिए रखता है |
| uppercase | **bool** | परिणामी हेक्साडेसिमल प्रतिनिधित्व में उपयोग किए जाने वाले अक्षरों के केस को निर्दिष्ट करता है |
| separator | const [String](../../string/)\& | परिणाम स्ट्रिंग में पड़ोसी बाइट्स की प्रत्येक जोड़ी के बीच डाला गया विभाजक के रूप में उपयोग किया जाने वाला स्ट्रिंग |

### रिटर्न मान

[String](../../string/) जिसमें निर्दिष्ट बाइट ऐरे का हेक्साडेसिमल प्रतिनिधित्व है

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) विधि

निर्दिष्ट बाइट ऐरे के मानों को निर्दिष्ट इंडेक्स से शुरू होकर उनके हेक्साडेसिमल स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है।

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जो बाइट्स को परिवर्तित करने के लिए रखता है |
| startIndex | int | [Index](../../index/) निर्दिष्ट ऐरे में वह स्थान जहाँ से परिवर्तन शुरू करना है |

### रिटर्न मान

[String](../../string/) जिसमें निर्दिष्ट ऐरे के निर्दिष्ट रेंज के तत्वों का हेक्साडेसिमल प्रतिनिधित्व है

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) विधि

निर्दिष्ट बाइट ऐरे के मानों की एक रेंज को उनके हेक्साडेसिमल स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है।

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जो बाइट्स को परिवर्तित करने के लिए रखता है |
| startIndex | int | [Index](../../index/) निर्दिष्ट ऐरे में वह स्थान जहाँ बाइट ऐरे तत्वों की रेंज का परिवर्तन शुरू होता है |
| length | int | बाइट ऐरे तत्वों को परिवर्तित करने वाली रेंज की लंबाई |

### रिटर्न मान

[String](../../string/) जिसमें निर्दिष्ट ऐरे के निर्दिष्ट रेंज के तत्वों का हेक्साडेसिमल प्रतिनिधित्व है

## देखें भी

* टाइपडेफ़ [ArrayPtr](../../arrayptr/)
* क्लास [String](../../string/)
* क्लास [BitConverter](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)