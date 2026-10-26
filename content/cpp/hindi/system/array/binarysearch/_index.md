---
title: BinarySearch()
second_title: Aspose.Slides for C++ API संदर्भ
description: सॉर्टेड एरे में द्विआधारी खोज करता है।
type: docs
weight: 612
url: /hi/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) विधि

सॉर्टेड एरे में द्विआधारी खोज करता है।

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | खोज करने के लिए सॉर्टेड एरे |
| item | const T\& | खोजने के लिए एक आइटम |

### रिटर्न मान

[Index](../../index/) खोजे गए आइटम का मान यदि वह पाया जाए, अन्यथा नकारात्मक पूर्णांक जो अगले आइटम (जिसका मान खोजे गए आइटम से बड़ा है) के इंडेक्स का बिटवाइस कॉम्प्लीमेंट होता है, या यदि कोई बड़ा आइटम नहीं है तो एरे में तत्वों की संख्या का बिटवाइस कॉम्प्लीमेंट।

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) विधि

अभी कार्यान्वित नहीं है।

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../arrayptr/)
* टाइपडिफ़ [SharedPtr](../../sharedptr/)
* क्लास [Array](../)
* क्लास [IComparer](../../../system.collections.generic/icomparer/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)