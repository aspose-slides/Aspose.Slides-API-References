---
title: WaitAll()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रदान किए गए Task ऑब्जेक्ट्स के सभी कार्य समाप्त होने की प्रतीक्षा करता है।
type: docs
weight: 170
url: /hi/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) फ़ंक्शन

प्रदान किए गए [Task](../task/) ऑब्जेक्ट्स के सभी कार्य समाप्त होने की प्रतीक्षा करता है।

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | विचार करने के लिए [Task](../task/) इंस्टेंस की एक एरे। |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | कार्य समाप्त होने तक प्रतीक्षा करते समय पर्यवेक्षण के लिए एक [CancellationToken](../../system.threading/cancellationtoken/)। |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) फ़ंक्शन

प्रदान किए गए [Task](../task/) ऑब्जेक्ट्स के सभी कार्य समाप्त होने की प्रतीक्षा करता है।

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | विचार करने के लिए [Task](../task/) इंस्टेंस की एक एरे। |

## देखें

* टाइपडिफ़ [ArrayPtr](../../system/arrayptr/)
* टाइपडिफ़ [TaskPtr](../../system/taskptr/)
* क्लास [CancellationToken](../../system.threading/cancellationtoken/)
* नेमस्पेस [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)