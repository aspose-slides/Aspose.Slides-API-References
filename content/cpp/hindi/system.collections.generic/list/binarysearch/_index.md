---
title: BinarySearch()
second_title: Aspose.Slides for C++ API संदर्भ
description: सॉर्ट की गई सूची में आइटम को खोजता है।
type: docs
weight: 339
url: /hi/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const विधि


सॉर्ट की गई सूची में आइटम को खोजता है।

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | const T\& | खोजने के लिए आइटम। |

### रिटर्न वैल्यू

[Index](../../../system/index/) सॉर्ट की गई सूची में आइटम का या निकटतम इंडेक्स का पूरक मान।

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const विधि


सॉर्ट की गई सूची में आइटम को खोजता है।

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | const T\& | खोजने के लिए आइटम। |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) उपयोग करने के लिए। |

### रिटर्न वैल्यू

[Index](../../../system/index/) सॉर्ट की गई सूची में आइटम का या निकटतम इंडेक्स का पूरक मान।

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const विधि


सॉर्ट की गई सूची में आइटम को खोजता है।

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) शुरुआत। |
| count | int | [Range](../../../system/range/) आकार। |
| item | const T\& | खोजने के लिए आइटम। |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) उपयोग करने के लिए। |

### रिटर्न वैल्यू

[Index](../../../system/index/) सॉर्ट की गई सूची में आइटम का या निकटतम इंडेक्स का पूरक मान।

## देखें भी

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [List](../)
* क्लास [IComparer](../../icomparer/)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)