---
title: Change()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टाइमर को पुनः निर्धारित करता है या रद्द करता है।
type: docs
weight: 14
url: /hi/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) विधि

टाइमर को पुनः निर्धारित करता है या रद्द करता है।

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) अगली बार कॉलबैक फ़ंक्शन के कॉल से पहले, मिलिसेकंड में; नकारात्मक मान टाइमर को रद्द कर देते हैं चाहे वह शेड्यूल हो। |
| period | **int64_t** | [Timeout](../../timeout/) लगातार कॉलबैक फ़ंक्शन के कॉल के बीच, मिलिसेकंड में; गैर-धनात्मक मान दर्शाते हैं कि टाइमर केवल एक बार चलना चाहिए। |

## Timer::Change(System::TimeSpan, System::TimeSpan) विधि

टाइमर को पुनः निर्धारित करता है या रद्द करता है।

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) अगली बार कॉलबैक फ़ंक्शन के कॉल से पहले; नकारात्मक मान टाइमर को रद्द कर देते हैं चाहे वह शेड्यूल हो। |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) लगातार कॉलबैक फ़ंक्शन के कॉल के बीच; गैर-धनात्मक मान दर्शाते हैं कि टाइमर केवल एक बार चलना चाहिए। |

## देखें भी

* क्लास [Timer](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)