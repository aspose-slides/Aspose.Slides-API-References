---
title: EnumValues
second_title: Aspose.Slides for C++ API संदर्भ
description: enum प्रकार E के enumeration स्थिरांकों के बारे में मेटा जानकारी प्रदान करता है।
type: docs
weight: 794
url: /hi/system/enumvalues/
---
## EnumValues क्लास

enum प्रकार **E** के enumeration स्थिरांक के बारे में मेटा जानकारी प्रदान करता है।

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| E | enumeration का प्रकार |

## मेथड्स

| Method | Description |
| --- | --- |
|  [EnumValues](./enumvalues/)() | एक उदाहरण बनाता है। |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | एक array लौटाता है जिसमें enumeration **E** के सभी नाम होते हैं। |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | एक निर्दिष्ट enumeration के स्थिरांक के नामों का array प्राप्त करता है। |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | निर्दिष्ट enumeration का अंतर्निहित प्रकार लौटाता है। |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | निर्दिष्ट enumeration का अंतर्निहित प्रकार लौटाता है। |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | निर्दिष्ट नाम वाले enum स्थिरांक का boxed मान लौटाता है। |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | निर्दिष्ट मान वाले enum स्थिरांक का boxed मान लौटाता है। |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | एक array लौटाता है जिसमें enumeration **E** के सभी मान होते हैं। |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | निर्दिष्ट enumeration प्रकार के सभी मानों वाला array लौटाता है। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | निर्दिष्ट नाम वाले enumeration स्थिरांक के मान का प्रतिनिधित्व करने वाला ऑब्जेक्ट लौटाता है। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | निर्दिष्ट 64-बिट unsigned integer मान को enumeration सदस्य में परिवर्तित करता है। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | निर्दिष्ट integer मान वाले ऑब्जेक्ट को enumeration सदस्य में परिवर्तित करता है। |
| virtual  [~EnumValues](./~enumvalues/)() | Destructor. |

## देखें

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)