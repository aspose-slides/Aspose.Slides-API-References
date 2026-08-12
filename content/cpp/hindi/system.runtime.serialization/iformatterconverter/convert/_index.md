---
title: Convert()
second_title: Aspose.Slides for C++ API संदर्भ
description: RTTI जानकारी।
type: docs
weight: 1
url: /hi/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) विधि


RTTI information.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | परिवर्तित होने वाला ऑब्जेक्ट। |
| type | const [TypeInfo](../../../system/typeinfo/)\& | वह [System::TypeInfo](../../../system/typeinfo/) जिसमें value को परिवर्तित किया जाना है। |

### रिटर्न वैल्यू

परिवर्तित मान।

## टिप्पणी

एक मान को दिए गए [System::TypeInfo](../../../system/typeinfo/) में परिवर्तित करता है।

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) विधि


एक मान को दिए गए [System::TypeCode](../../../system/typecode/) में परिवर्तित करता है।

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | परिवर्तित होने वाला ऑब्जेक्ट। |
| typeCode | [TypeCode](../../../system/typecode/) | वह [System::TypeCode](../../../system/typecode/) जिसमें value को परिवर्तित किया जाना है। |

### रिटर्न वैल्यू

परिवर्तित मान।

## देखें

* एनम [TypeCode](../../../system/typecode/)
* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [IFormatterConverter](../)
* नेमस्पेस [System::Runtime::Serialization](../../)
* लाइब्रेरी [Aspose.Slides](../../../)