---
title: GetEnvironmentVariables()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान प्रक्रिया से जुड़े सभी पर्यावरण चर नामों और उनके मानों को सम्मिलित करने वाला एक शब्दकोश लौटाता है।
type: docs
weight: 326
url: /hi/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() मेथड

वर्तमान प्रक्रिया से जुड़े सभी पर्यावरण चर नामों और उनके मानों को सम्मिलित करने वाला एक शब्दकोश लौटाता है।

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) मेथड

निर्दिष्ट स्थान से सभी पर्यावरण चरों के नामों और उनके मानों को सम्मिलित करने वाला एक शब्दकोश लौटाता है।

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | चरों का स्थान |

### रिटर्न वैल्यू

निर्दिष्ट स्थान से सभी पर्यावरण चरों के नामों और उनके मानों को सम्मिलित करने वाला एक शब्दकोश

## देखें

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* क्लास [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* क्लास [String](../../string/)
* Struct [Environment](../)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)