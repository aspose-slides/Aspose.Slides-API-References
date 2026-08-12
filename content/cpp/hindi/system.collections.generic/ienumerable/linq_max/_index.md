---
title: LINQ_Max()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक सामान्य क्रम के प्रत्येक तत्व पर रूपांतरण फ़ंक्शन को लागू करता है और अधिकतम प्राप्त मान लौटाता है।
type: docs
weight: 352
url: /hi/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) मेथड


एक सामान्य क्रम में प्रत्येक तत्व पर रूपांतरण फ़ंक्शन लागू करता है और अधिकतम प्राप्त मान लौटाता है।

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ResultType | सेलेक्टर द्वारा लौटाए गए मान का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | प्रत्येक तत्व पर लागू किए जाने वाले रूपांतरण फ़ंक्शन। |

### वापसी मान

क्रम में अधिकतम मान।

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) मेथड




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## देखें

* क्लास [Func](../../../system/func/)
* क्लास [IEnumerable](../)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)