---
title: Parse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समान 8-बिट साइन किए हुए पूर्णांक में बदलता है।
type: docs
weight: 1
url: /hi/system/sbyte/parse/
---
## SByte::Parse(const String\&) विधि

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समान 8-बिट साइन्ड इंटीजर में बदलता है।

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 8-बिट साइन्ड इंटीजर।

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) विधि

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान की गई फॉर्मेटिंग जानकारी का उपयोग करके समान 8-बिट साइन्ड इंटीजर में बदलता है।

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जिसमें स्ट्रिंग फॉर्मेट जानकारी होती है। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 8-बिट साइन्ड इंटीजर।

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) विधि

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) विधि

```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) विधि

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान की गई फॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके समान 8-बिट साइन्ड इंटीजर में बदलता है।

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जिसमें स्ट्रिंग फॉर्मेट जानकारी होती है। |

### रिटर्न मान

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 8-बिट साइन्ड इंटीज़र।

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) विधि

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) विधि

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) विधि

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## देखें

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)