---
title: GetDescription()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट मान वाले enumeration constant का नाम लौटाता है।
type: docs
weight: 53
url: /hi/system/enum/getdescription/
---
## Enum::GetDescription(T) विधि


निर्दिष्ट मान वाला enumeration constant का नाम लौटाता है।

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T | वह enum constant का मान जिसका नाम लौटाया जाना है |

### रिटर्न वैल्यू

निर्दिष्ट enum constant का नाम

## संबंधित

* Typedef [UnderlyingType](../underlyingtype/)
* क्लास [String](../../string/)
* स्ट्रक्ट [Enum](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)