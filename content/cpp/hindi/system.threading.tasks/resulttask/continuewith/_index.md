---
title: ContinueWith()
second_title: Aspose.Slides for C++ API संदर्भ
description: परिणाम कार्य पूरा होने पर निष्पादित होने वाली निरंतरता बनाता है।
type: docs
weight: 40
url: /hi/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method

परिणाम कार्य पूरा होने पर चलने वाली निरंतरता बनाता है।

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | इस कार्य के पूरा होने पर निष्पादित होने वाली क्रिया, जो इस परिणाम कार्य को प्राप्त करती है |

### रिटर्न मान

TaskPtr एक नया कार्य जो निरंतरता का प्रतिनिधित्व करता है

## टिप्पणियाँ

निरंतरता क्रिया इस [ResultTask](../) को प्राप्त करती है ताकि परिणाम मान तक पहुंच सके

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method

परिणाम कार्य पूरा होने पर चलने वाली निरंतरता बनाता है।

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TNewResult | कार्य निरंतरता का परिणाम प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | जब यह कार्य पूरा हो, निरंतरता परिणाम प्राप्त करने के लिए फ़ंक्शन, जो इस परिणाम कार्य को प्राप्त करता है |

### रिटर्न मान

RTaskPtr एक नया कार्य जो निरंतरता का प्रतिनिधित्व करता है

## टिप्पणियाँ

निरंतरता फ़ंक्शन इस [ResultTask](../) को प्राप्त करता है ताकि परिणाम मान तक पहुंच सके

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method

कार्य पूरा होने पर चलने वाली निरंतरता बनाता है।

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | इस कार्य के पूरा होने पर निष्पादित होने वाली क्रिया |

### रिटर्न मान

TaskPtr एक नया कार्य जो निरंतरता का प्रतिनिधित्व करता है

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method

कार्य पूरा होने पर चलने वाली निरंतरता बनाता है।

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TResult | कार्य परिणाम का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | जब यह कार्य पूरा हो, परिणाम प्राप्त करने के लिए फ़ंक्शन |

### रिटर्न मान

RTaskPtr एक नया कार्य जो निरंतरता का प्रतिनिधित्व करता है

## संबंधित देखें

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* क्लास [ResultTask](../)
* क्लास [Func](../../../system/func/)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)