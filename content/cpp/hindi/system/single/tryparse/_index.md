---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष single-precision floating-point मान में परिवर्तित करता है।
type: docs
weight: 14
url: /hi/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) विधि

निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष single-precision floating-point मान में परिवर्तित करता है।

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिये स्ट्रिंग। |
| result | **float**\& | वह single-precision floating-point चर जिसका संदर्भ परिणाम रखने के लिये उपयोग किया जाता है। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हो तो True, अन्यथा - false।

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) विधि

प्रदान किए गए फ़ॉर्मेटिंग जानकारी और number style का उपयोग करके, निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष single-precision floating-point मान में परिवर्तित करता है।

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिये स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मूल्यों का बिटवाइस संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | वह ऑब्जेक्ट का पॉइंटर जो स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |
| result | **float**\& | वह single-precision floating-point चर जिसका संदर्भ परिणाम रखने के लिये उपयोग किया जाता है। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हो तो True, अन्यथा - false।

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) विधि




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) विधि




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) विधि




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## देखें

* एनम [NumberStyles](../../../system.globalization/numberstyles/)
* टाइपडिफ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* स्ट्रक्ट [Single](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)