---
title: TrueForAll()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि क्या निर्दिष्ट एरे के सभी तत्व निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों को पूरा करते हैं।
type: docs
weight: 677
url: /hi/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) विधि

निर्धारित करता है कि क्या निर्दिष्ट एरे के सभी तत्व निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों को पूरा करते हैं।

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### आर्गुमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) तत्व, जिनके लिए शर्तों के विरुद्ध मिलान करना है |
| match | [System::Predicate](../../predicate/)\<T\> | एक प्रेडिकेट जो एरे तत्वों को शर्तों के विरुद्ध मिलान करने के लिए परिभाषित करता है |

### वापसी मान

true यदि एरे arr के सभी तत्व predicate match द्वारा परिभाषित शर्तों को पूरा करते हैं, अन्यथा false

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)