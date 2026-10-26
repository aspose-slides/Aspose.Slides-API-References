---
title: WhenAll()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक टास्क बनाता है जो सभी प्रदान किए गए टास्क के पूर्ण होने पर समाप्त हो जाएगा।
type: docs
weight: 196
url: /hi/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) फ़ंक्शन

एक टास्क बनाता है जो सभी प्रदान किए गए टास्क पूर्ण होने पर समाप्त होगा।

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | पूर्णता के लिए प्रतीक्षा करने वाले टास्क। |

### रिटर्न वैल्यू

एक टास्क जो सभी प्रदान किए गए टास्क की पूर्णता का प्रतिनिधित्व करता है।

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) फ़ंक्शन

एक टास्क बनाता है जो सभी प्रदान किए गए टास्क पूर्ण होने पर समाप्त होगा।

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | पूर्णता के लिए प्रतीक्षा करने वाले टास्क। |

### रिटर्न वैल्यू

एक टास्क जो सभी प्रदान किए गए टास्क की पूर्णता का प्रतिनिधित्व करता है।

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) फ़ंक्शन

एक टास्क बनाता है जो सभी प्रदान किए गए टास्क पूर्ण होने पर समाप्त होगा।

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TResult | पूर्ण हुए टास्क के परिणामों का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | पूर्णता के लिए प्रतीक्षा करने वाले टास्क। |

### रिटर्न वैल्यू

एक टास्क जो सभी टास्क के पूर्ण होने पर सभी परिणामों की एरे लौटाता है।

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) फ़ंक्शन

एक टास्क बनाता है जो सभी प्रदान किए गए टास्क पूर्ण होने पर समाप्त होगा।

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TResult | पूर्ण हुए टास्क के परिणामों का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | पूर्णता के लिए प्रतीक्षा करने वाले टास्क। |

### रिटर्न वैल्यू

एक टास्क जो सभी टास्क के पूर्ण होने पर सभी परिणामों की एरे लौटाता है।

## संबंधित देखें

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)