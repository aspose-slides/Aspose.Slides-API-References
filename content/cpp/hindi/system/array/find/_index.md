---
title: Find()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट एरे में पहले तत्व को खोजता है जो निर्दिष्ट प्रेडिकेट की शर्तों को पूरा करता है।
type: docs
weight: 651
url: /hi/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) मेथड

निर्दिष्ट एरे में पहली वह तत्व खोजता है जो निर्दिष्ट प्रेडिकेट की शर्तों को पूरा करता है।

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) में एक तत्व खोजने के लिए |
| match | [System::Predicate](../../predicate/)\<T\> | एक प्रेडिकेट जो एरे तत्वों को मिलाने की शर्तों को परिभाषित करता है |

### रिटर्न वैल्यू

एरे में पहला तत्व जिसका प्रतिलिपि प्रेडिकेट द्वारा परिभाषित शर्तों को पूरा करता है, अन्यथा प्रकार T का डिफॉल्ट मान

## संबल

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)