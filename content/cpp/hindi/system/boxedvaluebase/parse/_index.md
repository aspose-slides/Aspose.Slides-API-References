---
title: Parse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट enumeration के enumeration constant के मान को उसके निर्दिष्ट नाम के साथ बॉक्स करता है। एक पैरामीटर यह निर्दिष्ट करता है कि enumeration constant के नाम को दर्शाने वाली स्ट्रिंग को व्याख्या करते समय केस को नज़रअंदाज़ किया जाना चाहिए या नहीं।
type: docs
weight: 53
url: /hi/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) विधि


निर्दिष्ट enumeration के enumeration constant के मान को उसके निर्दिष्ट नाम के साथ बॉक्स करता है। एक पैरामीटर यह निर्दिष्ट करता है कि enumeration constant के नाम को दर्शाने वाली स्ट्रिंग को व्याख्या करते समय केस को नज़रअंदाज़ किया जाना चाहिए या नहीं।

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | enumeration के प्रकार को निर्दिष्ट करता है |
| str | const [String](../../string/)\& | उस enumeration constant का नाम, जिसका मान बॉक्स किया जाना है |
| ignoreCase | **bool** | स्ट्रिंग में enumeration constant के नाम को व्याख्या करते समय केस को नज़रअंदाज़ किया जाना चाहिए या नहीं, यह निर्दिष्ट करता है |

### रिटर्न वैल्यू

निर्दिष्ट enumeration constant के बॉक्स किए गए मान को दर्शाने वाले ऑब्जेक्ट का एक shared pointer

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) विधि


निर्दिष्ट enumeration के enumeration constant के मान को उसके निर्दिष्ट नाम के साथ बॉक्स करता है।

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | enumeration के प्रकार को निर्दिष्ट करता है |
| str | const [String](../../string/)\& | उस enumeration constant का नाम, जिसका मान बॉक्स किया जाना है |

### रिटर्न वैल्यू

निर्दिष्ट enumeration constant के बॉक्स किए गए मान को दर्शाने वाले ऑब्जेक्ट का एक shared pointer

## संबंधित देखें

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [Object](../../object/)
* क्लास [TypeInfo](../../typeinfo/)
* क्लास [String](../../string/)
* क्लास [BoxedValueBase](../)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)