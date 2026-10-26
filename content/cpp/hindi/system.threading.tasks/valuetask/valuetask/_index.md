---
title: ValueTask()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक खाली, अनिर्दिष्ट ValueTask बनाता है।
type: docs
weight: 1
url: /hi/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() कंस्ट्रक्टर

एक खाली, अनिर्दिष्ट [ValueTask](../) बनाता है।

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## टिप्पणियाँ

कार्य पूर्ण नहीं हुआ है और इसमें कोई परिणाम नहीं है। परिणाम प्राप्त करने का प्रयास करने पर एक अपवाद फेंका जाएगा।

## ValueTask::ValueTask(const TaskPtr\&) कंस्ट्रक्टर

[ValueTask](../) को [Task](../../task/) के एक साझा पॉइंटर से बनाता है।

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | रैप करने के लिए कार्य। खाली कार्य के लिए null हो सकता है। |

## टिप्पणियाँ

[ValueTask](../) प्रदान किए गए कार्य की स्थिति को दर्शाएगा।

## संबंधित देखें

* टाइपडिफ [TaskPtr](../../../system/taskptr/)
* क्लास [ValueTask](../)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)