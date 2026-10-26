---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस कार्य पर await के व्यवहार को कॉन्टेक्स्ट कैप्चर के अनुसार कॉन्फ़िगर करता है।
type: docs
weight: 144
url: /hi/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const विधि

Configures how awaits on this task should behave regarding context capture.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | कैप्चर किए गए कॉन्टेक्स्ट पर जारी रखना चाहिए या नहीं |

### रिटर्न वैल्यू

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) एक कॉन्फ़िगर किया गया awaitable

## संबंधित देखें

* क्लास [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* क्लास [Task](../)
* नामस्थान [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)