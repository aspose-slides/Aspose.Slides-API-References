---
title: TryParse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 32-bit साइनड इंटीजर में परिवर्तित करता है।
type: docs
weight: 14
url: /hi/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) विधि

निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को समकक्ष 32-बिट साइनड इंटीजर में परिवर्तित करता है।

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिये स्ट्रिंग। |
| result | **int32_t**\& | परिवर्तन के परिणाम को रखने वाले 32-बिट साइनड इंटीजर वेरिएबल का रेफ़रेंस। |

### रिटर्न वैल्यू

True यदि रूपांतरण सफल रहा, अन्यथा - false।

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) विधि

निर्दिष्ट स्ट्रिंग जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व है, को प्रदान की गई फ़ॉर्मेटिंग जानकारी और नंबर स्टाइल का उपयोग करके समकक्ष 32-बिट साइनड इंटीजर में परिवर्तित करता है।

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिये स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles एन्‍युम के मानों का बिटवाइज़ संयोजन जो नंबर के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जिसमें स्ट्रिंग फ़ॉर्मेट जानकारी होती है। |
| result | **int32_t**\& | परिवर्तन के परिणाम को रखने वाले 32-बिट साइनड इंटीजर वेरिएबल का रेफ़रेंस। |

### रिटर्न वैल्यू

True यदि रूपांतरण सफल रहा, अन्यथा - false।

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) विधि




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) विधि




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) विधि




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## देखें भी

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [Int32](../)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)