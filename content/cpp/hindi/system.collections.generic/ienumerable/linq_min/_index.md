---
title: LINQ_Min()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक जेनरिक क्रम में प्रत्येक तत्व पर एक ट्रांसफ़ॉर्म फ़ंक्शन को लागू करता है और न्यूनतम परिणामी मान वापस करता है।
type: docs
weight: 339
url: /hi/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method

एक जेनरिक सीक्वेंस के प्रत्येक तत्व पर एक ट्रांसफ़ॉर्म फ़ंक्शन को लागू करता है और न्यूनतम परिणामी मान लौटाता है।

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ResultType | सेलेक्टर द्वारा लौटाए गए मान के प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | प्रत्येक तत्व पर लागू करने के लिए एक ट्रांसफ़ॉर्म फ़ंक्शन। |

### रिटर्न वैल्यू

सीक्वेंस में न्यूनतम मान।

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## देखें

* क्लास [Func](../../../system/func/)
* क्लास [IEnumerable](../)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)