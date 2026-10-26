---
title: Timer()
second_title: Aspose.Slides for C++ API संदर्भ
description: कंस्ट्रक्टर। 
type: docs
weight: 1
url: /hi/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) निर्माता


निर्माता।

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | टाइमर द्वारा कॉल किए जाने वाला फ़ंक्शन। |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) निर्माता


निर्माता।

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | टाइमर द्वारा कॉल किए जाने वाला फ़ंक्शन। |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | कॉलबैक फ़ंक्शन तर्क। |
| dueTime | **int64_t** | [Timeout](../../timeout/) पहले कॉलबैक फ़ंक्शन के बुलाए जाने से पहले, मिलीसेकंड में; नकारात्मक मान टाईमर को निर्माण के बाद शेड्यूल नहीं करते हैं, इसलिए इसे बाद में फिर से शेड्यूल किया जा सकता है। |
| period | **int64_t** | [Timeout](../../timeout/) क्रमागत कॉलबैक फ़ंक्शन के बुलावे के बीच, मिलीसेकंड में; गैर-धनात्मक मान का अर्थ है कि टाईमर केवल एक बार चलाया जाना चाहिए। |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) निर्माता


निर्माता।

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | टाइमर द्वारा कॉल किए जाने वाला फ़ंक्शन। |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | कॉलबैक फ़ंक्शन तर्क। |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) पहले कॉलबैक फ़ंक्शन के बुलाए जाने से पहले; नकारात्मक मान टाईमर को निर्माण के बाद शेड्यूल नहीं करते हैं, इसलिए इसे बाद में फिर से शेड्यूल किया जा सकता है। |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) क्रमागत कॉलबैक फ़ंक्शन के बुलावे के बीच; गैर-धनात्मक मान का अर्थ है कि टाईमर केवल एक बार चलाया जाना चाहिए। |

## संबंधित देखें

* टाइपडिफ [TimerCallback](../../timercallback/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Timer](../)
* क्लास [Object](../../../system/object/)
* क्लास [TimeSpan](../../../system/timespan/)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)