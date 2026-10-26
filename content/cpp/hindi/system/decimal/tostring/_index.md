---
title: ToString()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑब्जेक्ट द्वारा प्रतिनिधित मान का स्ट्रिंग प्रतिनिधित्व लौटाता है।
type: docs
weight: 352
url: /hi/system/decimal/tostring/
---
## Decimal::ToString() const विधि

ऑब्जेक्ट द्वारा प्रतिनिधित मान की स्ट्रिंग प्रतिनिधित्व लौटाता है।

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const विधि

वर्तमान ऑब्जेक्ट को संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग करके स्ट्रिंग में परिवर्तित करता है।

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी प्रदान करने वाला [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट। |

### वापसी मान

वर्तमान ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व।

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const विधि

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const विधि

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const विधि

```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const विधि

निर्दिष्ट [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट द्वारा प्रदान की गई संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी और निर्दिष्ट स्ट्रिंग फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है।

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [String](../../string/)\& | स्ट्रिंग फ़ॉर्मेट। |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी प्रदान करने वाला [IFormatProvider](../../iformatprovider/) ऑब्जेक्ट। |

### वापसी मान

वर्तमान ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व।

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const विधि

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const विधि

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const विधि

```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## संबंधित

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [Decimal](../)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)