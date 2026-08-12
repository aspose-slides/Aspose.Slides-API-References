---
title: Parse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, उसे समतुल्य 32-बिट अनसाइन्ड इंटेजर में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system/uint32/parse/
---
## UInt32::Parse(const String\&) मेथड


निर्दिष्ट स्ट्रिंग जिसमें संख्या के स्ट्रिंग प्रतिनिधित्व है, उसे समतुल्य 32-बिट अनसाइन्ड इंटेजर में परिवर्तित करता है।

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 32-बिट अनसाइन्ड इंटेजर।

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) मेथड


निर्दिष्ट स्ट्रिंग जिसमें संख्या के स्ट्रिंग प्रतिनिधित्व है, उसे प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके समतुल्य 32-बिट अनसाइन्ड इंटेजर में परिवर्तित करता है।

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जो स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 32-बिट अनसाइन्ड इंटेजर।

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) मेथड




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) मेथड


निर्दिष्ट स्ट्रिंग जिसमें संख्या के स्ट्रिंग प्रतिनिधित्व है, उसे प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके समतुल्य 32-बिट अनसाइन्ड इंटेजर में परिवर्तित करता है।

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles एन्‍युम के मूल्यों का बिटवाइज संयोजन जो संख्या की स्ट्रिंग प्रस्तुतिकरण के अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जो स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 32-बिट अनसाइन्ड इंटेजर।

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड 




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) मेथड 




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## देखें भी

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)