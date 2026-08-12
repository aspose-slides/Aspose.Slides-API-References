---
title: ToObject()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट 64-बिट अनसाइनड इंटीजर मान को एक एनूमरेशन सदस्य में बदलता है।
type: docs
weight: 40
url: /hi/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) विधि


निर्दिष्ट 64-बिट अनसाइनड इंटीजर मान को एक एनूमरेशन सदस्य में परिवर्तित करता है।

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | वापसी के लिए एनूमरेशन प्रकार। |
| value | **uint64_t** | एनूमरेशन सदस्य में परिवर्तित करने के लिये मान। |

### Return Value

एनूमरेशन का एक उदाहरण जो मान पर सेट है।

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) विधि


निर्दिष्ट ऑब्जेक्ट को जिसके पास एक इंटीजर मान है, उसे एक एनूमरेशन सदस्य में परिवर्तित करता है।

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | वापसी के लिए एनूमरेशन प्रकार। |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | एनूमरेशन सदस्य में परिवर्तित करने के लिये मान। |

### Return Value

एक एनूमरेशन ऑब्जेक्ट जिसका दिया गया मान है।

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [Object](../../object/)
* क्लास [TypeInfo](../../typeinfo/)
* क्लास [EnumValuesBase](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)