---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समकक्ष 8-बिट अनसाइनड इंटीजर में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system/byte/parse/
---
## Byte::Parse(const String\&) मेथड

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समकक्ष 8-बिट अनसाइनड इंटीजर में परिवर्तित करता है।

```cpp
static uint8_t System::Byte::Parse(const String &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने हेतु स्ट्रिंग। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर 8-बिट अनसाइनड इंटीजर।

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) मेथड

प्रदान किए गए फ़ॉर्मैट जानकारी का उपयोग करके, निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 8-बिट अनसाइनड इंटीजर में परिवर्तित करता है।

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने हेतु स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | स्ट्रिंग फ़ॉर्मैट जानकारी रखने वाले ऑब्जेक्ट की पॉइंटर। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर 8-बिट अनसाइनड इंटीजर।

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) मेथड




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) मेथड

प्रदान किए गए फ़ॉर्मैट जानकारी और संख्या शैली का उपयोग करके, निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 8-बिट अनसाइनड इंटीजर में परिवर्तित करता है।

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने हेतु स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली निर्धारित करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | स्ट्रिंग फ़ॉर्मैट जानकारी रखने वाले ऑब्जेक्ट की पॉइंटर। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा दर्शाए गए संख्या के बराबर 8-बिट अनसाइनड इंटीजर।

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) मेथड




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## देखें

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)