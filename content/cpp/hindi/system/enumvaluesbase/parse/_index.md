---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: वह ऑब्जेक्ट लौटाता है जो निर्दिष्ट enumeration प्रकार के enumeration कॉन्स्टेंट के मान को, निर्दिष्ट नाम के साथ, दर्शाता है।
type: docs
weight: 27
url: /hi/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) मेथड

Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | वापसी के लिये enumeration मान के प्रकार को दर्शाने वाला [TypeInfo](../../typeinfo/) ऑब्जेक्ट |
| str | const [String](../../string/)\& | enum कॉन्स्टेंट का नाम |
| ignoreCase | **bool** | निर्दिष्ट करता है कि enum कॉन्स्टेंट के नाम की व्याख्या करते समय केस को नजरअंदाज किया जाना चाहिए या नहीं |

### रिटर्न वैल्यू

एक ऑब्जेक्ट जो उस enum कॉन्स्टेंट के मान को दर्शाता है जिसका नाम **str** में निर्दिष्ट है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../sharedptr/)
* क्लास [Object](../../object/)
* क्लास [TypeInfo](../../typeinfo/)
* क्लास [String](../../string/)
* क्लास [EnumValuesBase](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)