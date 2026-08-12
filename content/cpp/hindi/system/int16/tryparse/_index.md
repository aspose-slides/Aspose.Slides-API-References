---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 16-बिट साइन किए गए पूर्णांक में परिवर्तित करता है।
type: docs
weight: 14
url: /hi/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) विधि


निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 16-बिट साइन्ड पूर्णांक में बदलता है।

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| result | **int16_t**\& | परिणाम को रखने वाले 16-बिट साइन्ड पूर्णांक चर का संदर्भ। |

### रिटर्न वैल्यू

यदि परिवर्तन सफल हुआ तो true, अन्यथा false।

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) विधि


प्रदान की गई फ़ॉर्मेटिंग जानकारी और नंबर शैली का उपयोग करके, निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 16-बिट साइन्ड पूर्णांक में बदलता है।

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज़ संयोजन जो संख्या की स्ट्रिंग प्रतिनिधित्व के अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जो स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |
| result | **int16_t**\& | परिणाम को रखने वाले 16-बिट साइन्ड पूर्णांक चर का संदर्भ। |

### रिटर्न वैल्यू

यदि परिवर्तन सफल हुआ तो true, अन्यथा false।

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) विधि




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) विधि




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) विधि




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
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