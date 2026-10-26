---
title: LINQ_Average()
second_title: C++ के लिए Aspose.Slides एपीआई संदर्भ
description: संख्यात्मक मानों की अनुक्रम का औसत गणना करता है।
type: docs
weight: 365
url: /hi/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() मेथड

संख्यात्मक मानों की अनुक्रम का औसत गणना करता है।

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### रिटर्न वैल्यू

अनुक्रम में मानों का औसत।

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) मेथड

इनपुट अनुक्रम के प्रत्येक तत्व पर एक ट्रांसफ़ॉर्म फ़ंक्शन को बुलाकर प्राप्त मानों की अनुक्रम का औसत गणना करता है।

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ResultType | selector द्वारा लौटाए गए मान का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | प्रत्येक तत्व पर लागू करने के लिए एक ट्रांसफ़ॉर्म फ़ंक्शन। |

### रिटर्न वैल्यू

परिवर्तित मानों का औसत।

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) मेथड




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## देखें

* क्लास [IEnumerable](../)
* क्लास [Func](../../../system/func/)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)