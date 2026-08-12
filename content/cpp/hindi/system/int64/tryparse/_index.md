---
title: TryParse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निरूपित स्ट्रिंग जो संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को समतुल्य 64-bit साइन्ड इंटेजर में बदलता है।
type: docs
weight: 14
url: /hi/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) मेथड

निरूपित स्ट्रिंग जो संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को समतुल्य 64-bit साइन्ड इंटेजर में बदलता है।

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| result | **int64_t**\& | परिणाम रखे जाने वाले 64-bit साइन्ड इंटेजर वेरिएबल का रेफ़रेंस। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो true, अन्यथा false।

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) मेथड

निरूपित स्ट्रिंग जो संख्या का स्ट्रिंग प्रतिनिधित्व रखती है, को प्रदान की गई फ़ॉर्मेट जानकारी और नंबर शैली के साथ समतुल्य 64-bit साइन्ड इंटेजर में बदलता है।

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles इनेम के मानों का बिटवाइज संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमति योग्य शैली को निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट के पॉइंटर जो स्ट्रिंग फ़ॉर्मेट जानकारी रखता है। |
| result | **int64_t**\& | परिणाम रखे जाने वाले 64-bit साइन्ड इंटेजर वेरिएबल का रेफ़रेंस। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो true, अन्यथा false।

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) मेथड




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) मेथड




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) मेथड




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## देखें भी

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [Int64](../)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* नामस्थान [System](../../)
* Library [Aspose.Slides](../../../)