---
title: ConfigureAwait()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: इस परिणाम कार्य पर await कैसे व्यवहार करेंगे, इसे संदर्भ कैप्चर के संबंध में कॉन्फ़िगर करता है।
type: docs
weight: 27
url: /hi/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const मेथड

इस परिणाम कार्य पर await कैसे व्यवहार करेंगे, इसे संदर्भ कैप्चर के संबंध में कॉन्फ़िगर करता है।

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | क्या कैप्चर किए गए संदर्भ पर जारी रखा जाए |

### रिटर्न मान

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> परिणाम के लिए एक कॉन्फ़िगर किया गया awaitable

## टिप्पणियाँ

यह async/await पैटर्न के लिए संदर्भ प्रवाह पर बारीक नियंत्रण सक्षम करता है।

## देखें

* क्लास [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* क्लास [ResultTask](../)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)