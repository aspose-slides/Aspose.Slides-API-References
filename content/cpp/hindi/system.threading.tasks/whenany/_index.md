---
title: WhenAny()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक टास्क बनाता है जो तब पूरा होगा जब प्रदान किए गए किसी भी टास्क का निष्पादन समाप्त हो जाए।
type: docs
weight: 209
url: /hi/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) फ़ंक्शन

एक टास्क बनाता है जो तब पूरा होगा जब प्रदान किए गए किसी भी टास्क का निष्पादन समाप्त हो जायेगा।

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | पूरी होने की प्रतीक्षा करने वाले टास्क। |

### रिटर्न वैल्यू

एक टास्क जो प्रदान किए गए टास्क में से किसी एक की पूर्णता को दर्शाता है।

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) फ़ंक्शन

एक टास्क बनाता है जो तब पूरा होगा जब प्रदान किए गए किसी भी टास्क का निष्पादन समाप्त हो जायेगा।

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | पूरी होने की प्रतीक्षा करने वाले टास्क। |

### रिटर्न वैल्यू

एक टास्क जो प्रदान किए गए टास्क में से किसी एक की पूर्णता को दर्शाता है।

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) फ़ंक्शन

एक टास्क बनाता है जो तब पूरा होगा जब प्रदान किए गए किसी भी टास्क का निष्पादन समाप्त हो जायेगा।

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### टेम्पलेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| TResult | पूर्ण हुए टास्क के परिणाम का प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | पूरी होने की प्रतीक्षा करने वाले टास्क। |

### रिटर्न वैल्यू

एक टास्क जो किसी भी टास्क के पूर्ण होने पर पहला पूर्ण हुआ टास्क लौटाता है।

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) फ़ंक्शन

एक टास्क बनाता है जो तब पूरा होगा जब प्रदान किए गए किसी भी टास्क का निष्पादन समाप्त हो जायेगा।

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### टेम्पलेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| TResult | पूर्ण हुए टास्क के परिणाम का प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | पूरी होने की प्रतीक्षा करने वाले टास्क। |

### रिटर्न वैल्यू

एक टास्क जो किसी भी टास्क के पूर्ण होने पर पहला पूर्ण हुआ टास्क लौटाता है।

## संबंधित देखें

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* क्लास [IEnumerable](../../system.collections.generic/ienumerable/)
* नेमस्पेस [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)