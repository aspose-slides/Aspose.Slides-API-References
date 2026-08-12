---
title: Parse()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समकक्ष 16-बिट अनसाइन्ड इंटीजर में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system/uint16/parse/
---
## UInt16::Parse(const String\&) मेथड

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समकक्ष 16-बिट अनसाइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |

### वापसी मान

वह 16-बिट अनसाइन्ड इंटीजर जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर है।

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) मेथड

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान किए गए स्वरूपण जानकारी का उपयोग करके समकक्ष 16-बिट अनसाइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक पोइंटर जो ऐसी वस्तु की ओर इशारा करता है जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी होती है। |

### वापसी मान

वह 16-बिट अनसाइन्ड इंटीजर जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर है।

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) मेथड




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) मेथड

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान किए गए स्वरूपण जानकारी और संख्या शैली का उपयोग करके समकक्ष 16-बिट अनसाइन्ड इंटीजर में परिवर्तित करता है।

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles एनम के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक पोइंटर जो ऐसी वस्तु की ओर इशारा करता है जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी होती है। |

### वापसी मान

वह 16-बिट अनसाइन्ड इंटीजर जो निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर है।

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) मेथड




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## संबंधित देखें

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)