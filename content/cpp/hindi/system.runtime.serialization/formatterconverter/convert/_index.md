---
title: Convert()
second_title: Aspose.Slides for C++ API संदर्भ
description: "दिए गए System::TypeInfo में मान को परिवर्तित करता है।"
type: docs
weight: 1
url: /hi/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method

किसी मान को दिए हुए [System::TypeInfo](../../../system/typeinfo/) में परिवर्तित करता है।

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | परिवर्तित की जाने वाली वस्तु। |
| type | const [TypeInfo](../../../system/typeinfo/)\& | वह [System::TypeInfo](../../../system/typeinfo/) जिसमें मान को परिवर्तित किया जाना है। |

### रिटर्न मान

परिवर्तित मान।

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method

किसी मान को दिए हुए [System::TypeCode](../../../system/typecode/) में परिवर्तित करता है।

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | परिवर्तित की जाने वाली वस्तु। |
| typeCode | [TypeCode](../../../system/typecode/) | वह [System::TypeCode](../../../system/typecode/) जिसमें मान को परिवर्तित किया जाना है। |

### रिटर्न मान

परिवर्तित मान।

## देखें

* एनम [TypeCode](../../../system/typecode/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [FormatterConverter](../)
* नेमस्पेस [System::Runtime::Serialization](../../)
* लाइब्रेरी [Aspose.Slides](../../../)