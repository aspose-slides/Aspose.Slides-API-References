---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समकक्ष 16-बिट साइन्ड इंटीजर में बदलता है।
type: docs
weight: 1
url: /hi/system/int16/parse/
---
## Int16::Parse(const String\&) मेथड

निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समकक्ष 16-बिट साइन्ड इंटीजर में बदलता है।

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 16-बिट साइन्ड इंटीजर।

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) मेथड

निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान की गई फ़ॉर्मेटिंग जानकारी का उपयोग करके समकक्ष 16-बिट साइन्ड इंटीजर में बदलता है।

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | स्ट्रिंग फ़ॉर्मेट जानकारी वाले ऑब्जेक्ट की पोइंटर। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 16-बिट साइन्ड इंटीजर।

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) मेथड




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) मेथड

निर्दिष्ट स्ट्रिंग, जिसमें किसी संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को प्रदान की गई फ़ॉर्मेटिंग जानकारी और संख्या शैली का उपयोग करके समकक्ष 16-बिट साइन्ड इंटीजर में बदलता है।

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिये स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइस संयोजन, जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमति दी गई शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | स्ट्रिंग फ़ॉर्मेट जानकारी वाले ऑब्जेक्ट की पोइंटर। |

### रिटर्न वैल्यू

निर्दिष्ट स्ट्रिंग द्वारा प्रतिनिधित्व की गई संख्या के बराबर 16-बिट साइन्ड इंटीजर।

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) मेथड




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) मेथड




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) मेथड




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## संबंधित देखें

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)