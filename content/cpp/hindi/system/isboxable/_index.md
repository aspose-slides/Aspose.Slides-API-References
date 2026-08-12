---
title: IsBoxable
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: उस टेम्पलेट प्रेडिकेट जो जाँचता है कि निर्दिष्ट प्रकार की बॉक्सिंग समर्थित है या नहीं।
type: docs
weight: 1665
url: /hi/system/isboxable/
---
## IsBoxable struct


निर्दिष्ट प्रकार के बॉक्सिंग का समर्थन किया जाता है या नहीं, यह जांचने वाला टेम्पलेट भविष्यवक्ता।

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जाँचने के लिए प्रकार |

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)