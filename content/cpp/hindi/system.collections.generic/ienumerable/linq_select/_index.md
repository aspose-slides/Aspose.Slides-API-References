---
title: LINQ_Select()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अनुक्रम के तत्वों को बदलता है।
type: docs
weight: 248
url: /hi/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) विधि

एक अनुक्रम के तत्वों को बदलता है।

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ResultType | **selector** द्वारा लौटाए गए मान का प्रकार। |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | एक परिवर्तन फ़ंक्शन। |

### रिटर्न मान

एक [IEnumerable](../) जो **selector** फ़ंक्शन द्वारा लौटाए गए तत्वों को समाहित करता है।

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) विधि

एक अनुक्रम के प्रत्येक तत्व को उसके सूचकांक को शामिल करके नई रूप में बदलता है।

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| ResultType | **selector** द्वारा लौटाए गए मान का प्रकार। |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | एक परिवर्तन फ़ंक्शन। |

### रिटर्न मान

एक [IEnumerable](../) जो **selector** फ़ंक्शन द्वारा लौटाए गए तत्वों को समाहित करता है।

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) विधि

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) विधि

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IEnumerable](../)
* क्लास [Func](../../../system/func/)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)