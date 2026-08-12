---
title: TryParse()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जो किसी संख्या के स्ट्रिंग प्रतिनिधित्व को रखती है, को समकक्ष 32-bit अनसाइनड इंटेजर में परिवर्तित करती है।
type: docs
weight: 14
url: /hi/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) method


निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को समतुल्य 32-बिट अनसाइनड इंटेजर में परिवर्तित करता है।

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | रूपांतरित करने के लिए स्ट्रिंग। |
| result | **uint32_t**\& | उस 32-बिट अनसाइनड इंटेजर वेरिएबल का संदर्भ जहाँ रूपांतरण का परिणाम रखा जाता है। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो True, अन्यथा - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) method


निर्दिष्ट स्ट्रिंग जो किसी संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को प्रदान किए गए फॉर्मेटिंग जानकारी और नंबर स्टाइल का उपयोग करके समतुल्य 32-बिट अनसाइनड इंटेजर में परिवर्तित करता है।

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | रूपांतरित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles एन्हुम के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व के अनुमत शैली को निर्धारित करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जो स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |
| result | **uint32_t**\& | उस 32-बिट अनसाइनड इंटेजर वेरिएबल का संदर्भ जहाँ रूपांतरण का परिणाम रखा जाता है। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो True, अन्यथा - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## संदर्भ देखें

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)