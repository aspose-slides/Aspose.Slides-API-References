---
title: TryParse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 16-बिट अनसाइन्ड इंटेजर में बदलता है।
type: docs
weight: 14
url: /hi/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) method

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 16-बिट अनसाइन्ड इंटेजर में बदलता है।

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिए स्ट्रिंग। |
| result | **uint16_t**\& | 16-बिट अनसाइन्ड इंटेजर वेरिएबल का रेफरेंस जहाँ रूपांतरण का परिणाम रखा जाता है। |

### Return Value

यदि रूपांतरण सफल हो तो true, अन्यथा - false।

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) method

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को प्रदान की गई फ़ॉर्मेट जानकारी और नंबर स्टाइल का उपयोग करके समकक्ष 16-बिट अनसाइन्ड इंटेजर में बदलता है।

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | बदलने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles एनीम के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमति प्राप्त शैली निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जो स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |
| result | **uint16_t**\& | 16-बिट अनसाइन्ड इंटेजर वेरिएबल का रेफरेंस जहाँ रूपांतरण का परिणाम रखा जाता है। |

### Return Value

यदि रूपांतरण सफल हो तो true, अन्यथा - false।

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)