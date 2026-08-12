---
title: CancellationTokenRegistration
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: रद्दीकरण टोकन कॉलबैक के लिए पंजीकरण का प्रतिनिधित्व करता है।
type: docs
weight: 27
url: /hi/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration क्लास

रद्दीकरण टोकन कॉलबैक के लिए एक पंजीकरण का प्रतिनिधित्व करता है।

```cpp
class CancellationTokenRegistration
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Dispose](./dispose/)() | पंजीकरण को नष्ट करता है और संबंधित [CancellationTokenSource](../cancellationtokensource/) से कॉलबैक को हटाता है। इस विधि को कॉल करने के बाद, पंजीकृत कॉलबैक अब नहीं बुलाया जाएगा जब संबंधित [CancellationTokenSource](../cancellationtokensource/) रद्द किया जाता है। |

## टिप्पणियाँ

यह क्लास एक रद्दीकरण टोकन से कॉलबैक को डीरजिस्टर्ड करने की अनुमति देती है। नष्ट किए जाने पर, यह संबंधित [CancellationTokenSource](../cancellationtokensource/) से कॉलबैक को हटाता है। इस क्लास को सीधे नहीं बनाना चाहिए - यह [CancellationToken](../cancellationtoken/) पंजीकरण विधियों द्वारा लौटाया जाता है।

## देखें

* नामस्थान [System::Threading](../)
* लाइब्रेरी [Aspose.Slides](../../)