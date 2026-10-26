---
title: ConfigureAwait()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: इस टास्क के लिए एक awaiter को कॉन्फ़िगर करता है।
type: docs
weight: 92
url: /hi/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const मेथड

इस टास्क के लिए एक awaiter को कॉन्फ़िगर करता है।

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true को मूल रूप से कैप्चर किए गए संदर्भ में निरंतरता को पुनः स्थापित करने के प्रयास के लिए; अन्यथा, false. |

### रिटर्न वैल्यू

ConfiguredResultValueTaskAwaitable<T> वह ऑब्जेक्ट जो इस टास्क के लिए awaiters के व्यवहार को कॉन्फ़िगर करता है।

## संबंधित देखें

* क्लास [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* क्लास [ResultValueTask](../)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)