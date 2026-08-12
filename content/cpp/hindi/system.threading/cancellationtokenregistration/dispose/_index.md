---
title: Dispose()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: पंजीकरण को निरस्त करता है और संबंधित CancellationTokenSource से कॉलबैक को हटाता है। इस विधि को कॉल करने के बाद, पंजीकृत कॉलबैक तब नहीं बुलाया जाएगा जब संबंधित CancellationTokenSource को रद्द किया जाता है।
type: docs
weight: 1
url: /hi/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() विधि


पंजीकरण को निरस्त करता है और संबंधित [CancellationTokenSource](../../cancellationtokensource/) से कॉलबैक को हटाता है। इस विधि को कॉल करने के बाद, पंजीकृत कॉलबैक तब नहीं बुलाया जाएगा जब संबंधित [CancellationTokenSource](../../cancellationtokensource/) रद्द किया जाता है।

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## टिप्पणी



इस विधि को कई बार कॉल करना सुरक्षित है - बाद में किए गए कॉल्स का कोई असर नहीं होगा। 

## संबंधित देखें

* क्लास [CancellationTokenRegistration](../)
* नेमस्पेस [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)