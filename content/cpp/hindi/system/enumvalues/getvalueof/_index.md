---
title: GetValueOf()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट नाम वाले enum स्थिरांक का बॉक्स्ड मान लौटाता है।
type: docs
weight: 53
url: /hi/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const विधि


निर्दिष्ट नाम वाले enum स्थिरांक का बॉक्स्ड मान वापस करता है।

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../string/)\& | enum स्थिरांक का नाम |
| ignoreCase | **bool** | निर्दिष्ट करता है कि enum स्थिरांक के नाम को व्याख्या करते समय केस को नज़रअंदाज़ किया जाए या नहीं |

### रिटर्न मान

एक बॉक्स्ड मान जो **str** में निर्दिष्ट नाम वाला enum स्थिरांक है।

## EnumValues::GetValueOf(long) const विधि


निर्दिष्ट मान वाले enum स्थिरांक का बॉक्स्ड मान वापस करता है।

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| val | long | enum स्थिरांक का मान |

### रिटर्न मान

एक बॉक्स्ड मान जो **str** में निर्दिष्ट वैल्यू वाला enum स्थिरांक है।

## देखें

* टाइपडेफ [SharedPtr](../../sharedptr/)
* क्लास [Object](../../object/)
* क्लास [String](../../string/)
* क्लास [EnumValues](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)