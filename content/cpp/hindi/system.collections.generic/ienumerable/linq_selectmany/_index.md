---
title: LINQ_SelectMany()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अनुक्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी अनुक्रमों को एक ही अनुक्रम में जोड़ता है।
type: docs
weight: 300
url: /hi/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method

एक अनुक्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी अनुक्रमों को एक ही अनुक्रम में संयोजित करता है।

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ResultType | वह प्रकार जो **selector** द्वारा लौटाई गई मान का है। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | एक ट्रांसफ़ॉर्म फ़ंक्शन। |

### रिटर्न मान

एक [IEnumerable](../) जो इनपुट अनुक्रम के प्रत्येक तत्व पर वन-टू-मैनी प्रोजेक्शन फ़ंक्शन को कॉल करने के परिणाम को समाहित करता है।

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IEnumerable](../)
* क्लास [Func](../../../system/func/)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)