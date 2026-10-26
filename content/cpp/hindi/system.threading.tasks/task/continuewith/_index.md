---
title: ContinueWith()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: जब टास्क पूर्ण हो जाता है तो एक निरंतरता बनाता है जो निष्पादित होती है।
type: docs
weight: 118
url: /hi/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) मेथड

जब टास्क पूर्ण हो जाता है तो एक निरंतरता बनाता है जो निष्पादित होती है।

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | जब यह टास्क पूर्ण हो तब निष्पादित होने वाला Action |

### Return Value

TaskPtr निरंतरता को दर्शाने वाला एक नया टास्क

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) मेथड

जब टास्क पूर्ण हो जाता है तो एक निरंतरता बनाता है जो निष्पादित होती है।

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| TResult | टास्क परिणाम का प्रकार |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | जब यह टास्क पूर्ण हो तब परिणाम प्राप्त करने वाला फ़ंक्शन |

### Return Value

RTaskPtr नया टास्क जो निरंतरता को दर्शाता है

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* क्लास [Task](../)
* क्लास [Func](../../../system/func/)
* नामस्थान [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)