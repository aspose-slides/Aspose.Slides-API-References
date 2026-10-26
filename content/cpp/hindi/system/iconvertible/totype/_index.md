---
title: ToType()
second_title: Aspose.Slides for C++ API संदर्भ
description: "इस इंस्टेंस के मान को निर्दिष्ट System::Type के एक System::Object में परिवर्तित करता है जिसका मान समतुल्य है, निर्दिष्ट संस्कृति-विशिष्ट स्वरूपण जानकारी का उपयोग करके।"
type: docs
weight: 209
url: /hi/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) method

इस इंस्टेंस के मान को निर्दिष्ट System::Type के एक [System::Object](../../object/) में परिवर्तित करता है जिसका मान समतुल्य है, निर्दिष्ट संस्कृति-विशिष्ट स्वरूपण जानकारी का उपयोग करके।

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type जिसके लिए इस इंस्टेंस का मान परिवर्तित किया जाता है। |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | एक [System::IFormatProvider](../../iformatprovider/) इंटरफ़ेस कार्यान्वयन जो संस्कृति-विशिष्ट स्वरूपण जानकारी प्रदान करता है। |

### रिटर्न मान

[System::Object](../../object/) प्रकार conversionType का एक इंस्टेंस जिसका मान इस इंस्टेंस के मान के समतुल्य है।

## देखें

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [Object](../../object/)
* क्लास [TypeInfo](../../typeinfo/)
* क्लास [IFormatProvider](../../iformatprovider/)
* क्लास [IConvertible](../)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)