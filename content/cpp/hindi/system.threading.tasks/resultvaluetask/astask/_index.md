---
title: AsTask()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस ResultValueTask को ResultTask<T> के एक शेयर्ड पॉइंटर में बदलता है।
type: docs
weight: 79
url: /hi/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const विधि

इस [ResultValueTask](../) को ResultTask<T> के एक शेयर्ड पॉइंटर में बदलता है।

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### वापसी मान

RTaskPtr<T> एक शेयर्ड पॉइंटर जो इस ऑपरेशन का प्रतिनिधित्व करता है।

## टिप्पणियाँ

यदि [ResultValueTask](../) में प्रत्यक्ष परिणाम होता है, तो उस परिणाम के साथ एक पूर्ण टास्क बनाता है। यदि इसमें एक टास्क है, तो उस टास्क का एक शेयर्ड पॉइंटर वापस करता है।

## संबंधित देखें

* टाइपडिफ़ [RTaskPtr](../../../system/rtaskptr/)
* क्लास [ResultValueTask](../)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)