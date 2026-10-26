---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट string जिसमें संख्या का string प्रतिनिधित्व है, को समतुल्य 64-bit unsigned integer में बदलता है।
type: docs
weight: 1
url: /hi/system/uint64/parse/
---
## UInt64::Parse(const String\&) विधि

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व हो, को समतुल्य 64-बिट अनसाइन्ड इंटेजर में बदलता है।

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व किए गए संख्या के बराबर 64-बिट अनसाइन्ड इंटेजर।

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) विधि

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व हो, को प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके समतुल्य 64-बिट अनसाइन्ड इंटेजर में बदलता है।

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट के पॉइंटर जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी है। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व किए गए संख्या के बराबर 64-बिट अनसाइन्ड इंटेजर।

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) विधि



```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि



```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) विधि



```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) विधि

प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व हो, को समतुल्य 64-बिट अनसाइन्ड इंटेजर में बदलता है।

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट के पॉइंटर जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी है। |

### वापसी मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व किए गए संख्या के बराबर 64-बिट अनसाइन्ड इंटेजर।

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) विधि



```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि



```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) विधि



```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## संबंधित देखें

* एनम [NumberStyles](../../../system.globalization/numberstyles/)
* टाइपडिफ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* स्ट्रक्ट [UInt64](../)
* नेसस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)