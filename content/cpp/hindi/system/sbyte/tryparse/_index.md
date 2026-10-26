---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग, जिसमें संख्या का स्ट्रिंग प्रतिनिधित्व होता है, को समकक्ष 8-बिट साइन्ड इंटीजर में परिवर्तित करता है।
type: docs
weight: 14
url: /hi/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) मेथड

Converts the specified string containing the string representation of a number to the equivalent 8-bit signed integer.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | रूपांतरित करने के लिये स्ट्रिंग। |
| result | **int8_t**\& | एक 8-बिट साइन्ड इंटीजर वेरिएबल का रेफ़रेंस जहाँ रूपांतरण का परिणाम रखा जाता है। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो true, अन्यथा false।

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) मेथड

Converts the specified string containing the string representation of a number to the equivalent 8-bit signed integer using the provided formatting information and number style.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | रूपांतरित करने के लिये स्ट्रिंग। |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum के मानों का बिटवाइज़ संयोजन जो संख्या के स्ट्रिंग प्रतिनिधित्व की अनुमत शैली निर्दिष्ट करता है। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | एक ऑब्जेक्ट का पॉइंटर जो स्ट्रिंग फॉर्मेट सूचना रखता है। |
| result | **int8_t**\& | एक 8-बिट साइन्ड इंटीजर वेरिएबल का रेफ़रेंस जहाँ रूपांतरण का परिणाम रखा जाता है। |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो true, अन्यथा false।

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) मेथड

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) मेथड

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) मेथड

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## देखें भी

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)