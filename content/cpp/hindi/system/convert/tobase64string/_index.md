---
title: ToBase64String()
second_title: Aspose.Slides for C++ API संदर्भ
description: Base-64 निर्दिष्ट बाइट एरे में तत्वों को एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है।
type: docs
weight: 40
url: /hi/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) मेथड

Base-64 निर्दिष्ट बाइट एरे में तत्वों को एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है।

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### आर्ग्युमेंट

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | एन्कोड करने हेतु बाइट्स की एरे |
| insert_line_breaks | **bool** | निर्दिष्ट करता है कि क्या आउटपुट स्ट्रिंग में प्रत्येक 76 Base-64 अक्षरों के बाद लाइन ब्रेक कैरेक्टर सम्मिलित किए जाएँ |

### रिटर्न वैल्यू

इनपुट एरे की Base-64 एन्कोडेड प्रतिनिधित्व वाली स्ट्रिंग

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) मेथड

Base-64 निर्दिष्ट बाइट एरे में तत्वों की सीमा को एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है।

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### आर्ग्युमेंट

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | एन्कोड करने हेतु तत्वों की सीमा वाली बाइट्स की एरे |
| offset_in | int | इनपुट एरे में उस तत्व का इंडेक्स जहाँ से एन्कोड करने की सीमा शुरू होती है |
| length | int | एन्कोड करने वाली तत्वों की सीमा की लंबाई |
| insert_line_breaks | **bool** | निर्दिष्ट करता है कि क्या आउटपुट स्ट्रिंग में प्रत्येक 76 Base-64 अक्षरों के बाद लाइन ब्रेक कैरेक्टर सम्मिलित किए जाएँ |

### रिटर्न वैल्यू

इनपुट एरे की सीमा के Base-64 एन्कोडेड प्रतिनिधित्व वाली स्ट्रिंग

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) मेथड

Base-64 निर्दिष्ट बाइट एरे में तत्वों को एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है।

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### आर्ग्युमेंट

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | एन्कोड करने हेतु बाइट्स की एरे |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 एन्कोडेड डेटा के फॉर्मेटिंग विकल्प निर्दिष्ट करता है |

### रिटर्न वैल्यू

इनपुट एरे की Base-64 एन्कोडेड प्रतिनिधित्व वाली स्ट्रिंग

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) मेथड

Base-64 निर्दिष्ट बाइट एरे में तत्वों की सीमा को एन्कोड करता है और एन्कोडेड डेटा को स्ट्रिंग के रूप में लौटाता है।

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### आर्ग्युमेंट

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | एन्कोड करने हेतु तत्वों की सीमा वाली बाइट्स की एरे |
| offset_in | int | इनपुट एरे में उस तत्व का इंडेक्स जहाँ से एन्कोड करने की सीमा शुरू होती है |
| length | int | एन्कोड करने वाली तत्वों की सीमा की लंबाई |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 एन्कोडेड डेटा के फॉर्मेटिंग विकल्प निर्दिष्ट करता है |

### रिटर्न वैल्यू

इनपुट एरे की सीमा के Base-64 एन्कोडेड प्रतिनिधित्व वाली स्ट्रिंग

## देखें भी

* एन्यूम [Base64FormattingOptions](../../base64formattingoptions/)
* टाइपडिफ [ArrayPtr](../../arrayptr/)
* क्लास [String](../../string/)
* स्ट्रक्ट [Convert](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)