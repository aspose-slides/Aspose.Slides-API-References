---
title: FindAll()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट प्रीडिकेट द्वारा परिभाषित शर्तों से मेल खाने वाले सभी तत्वों को प्राप्त करता है।
type: docs
weight: 664
url: /hi/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) विधि

निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों से मेल खाने वाले सभी तत्वों को पुनः प्राप्त करता है।

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) तत्वों की खोज करने के लिए |
| match | [System::Predicate](../../predicate/)\<T\> | एक प्रेडिकेट जो एरे तत्वों को मिलाने की शर्तें निर्धारित करता है |

### Return Value

एक [Array](../) जिसमें सभी तत्व शामिल हैं जो निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों से मेल खाते हैं, यदि पाया गया हो; अन्यथा, एक खाली [Array](../)।

## अन्य देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)