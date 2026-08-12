---
title: EnumValuesBase
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बेस क्लास जो enumeration प्रकार की मेटा जानकारी का प्रतिनिधित्व करने वाले क्लास के लिए है।
type: docs
weight: 807
url: /hi/system/enumvaluesbase/
---
## EnumValuesBase वर्ग

एक वर्ग जो enumeration प्रकार की मेटा-सूचना का प्रतिनिधित्व करता है।

```cpp
class EnumValuesBase
```

## विधियां

| Method | Description |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | एक निर्दिष्ट enumeration में स्थिरांक के नामों की एक array प्राप्त करता है। |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | निर्दिष्ट enumeration का मूल प्रकार लौटाता है। |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | निर्दिष्ट enumeration प्रकार के सभी मानों को समाहित करने वाली एक array लौटाता है। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | निर्दिष्ट नाम के साथ निर्दिष्ट enumeration प्रकार के enumeration constant के मान का प्रतिनिधित्व करने वाला एक ऑब्जेक्ट लौटाता है। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | निर्दिष्ट 64-bit unsigned integer मान को enumeration सदस्य में परिवर्तित करता है। |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | एक integer मान वाले निर्दिष्ट ऑब्जेक्ट को enumeration सदस्य में परिवर्तित करता है। |
## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)