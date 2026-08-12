---
title: FromException()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट अपवाद के साथ पूर्ण हुआ एक टास्क बनाता है।
type: docs
weight: 131
url: /hi/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) फ़ंक्शन

एक टास्क बनाता है जो निर्दिष्ट अपवाद के साथ पूर्ण हो चुका है।

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | टास्क को पूर्ण करने के लिए अपवाद। |

### वापसी मान

एक त्रुटिपूर्ण टास्क।

## System::Threading::Tasks::FromException(const Exception\&) फ़ंक्शन

एक टास्क बनाता है जो निर्दिष्ट अपवाद और परिणाम प्रकार के साथ पूर्ण हो चुका है।

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TResult | टास्क के परिणाम का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | टास्क को पूर्ण करने के लिए अपवाद। |

### वापसी मान

एक त्रुटिपूर्ण टास्क जिसमें निर्दिष्ट परिणाम प्रकार हो।

## देखें

* टाइपडिफ़ [TaskPtr](../../system/taskptr/)
* टाइपडिफ़ [Exception](../../system/exception/)
* टाइपडिफ़ [RTaskPtr](../../system/rtaskptr/)
* नामस्थान [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)