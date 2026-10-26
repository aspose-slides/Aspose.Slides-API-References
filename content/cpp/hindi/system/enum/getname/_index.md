---
title: GetName()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट मान वाले एन्‍युमेरेशन कॉन्स्टैंट का नाम लौटाता है।
type: docs
weight: 40
url: /hi/system/enum/getname/
---
## Enum::GetName(T) मेथड

निर्दिष्ट मान वाले एन्‍युमेरेशन कॉन्स्टैंट का नाम लौटाता है।

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T | उस enum कॉन्स्टैंट का मान जिसका नाम वापस किया जाना है |

### रिटर्न वैल्यू

निर्दिष्ट enum कॉन्स्टैंट का नाम

## संबंधित

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)