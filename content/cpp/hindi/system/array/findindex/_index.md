---
title: FindIndex()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट सरणी में पहला तत्व खोजता है जो निर्दिष्ट प्रेडिकेट की शर्तों को संतुष्ट करता है।
type: docs
weight: 638
url: /hi/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) मेथड

निर्दिष्ट सरणी में पहला तत्व खोजता है जो निर्दिष्ट प्रेडिकेट की शर्तों को संतुष्ट करता है।

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) में एक तत्व खोजने के लिए |
| match | [System::Predicate](../../predicate/)\<T\> | ऐसा प्रेडिकेट जो सरणी तत्वों को मिलाने की शर्तों को परिभाषित करता है |

### रिटर्न वैल्यू

पहले तत्व का इंडेक्स जो प्रेडिकेट द्वारा परिभाषित शर्तों को संतुष्ट करता है, नहीं तो -1

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* क्लास [Array](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)