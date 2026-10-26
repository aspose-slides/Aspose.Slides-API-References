---
title: WaitAny()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रदान किए गए Task ऑब्जेक्ट्स में से किसी एक के निष्पादन के पूर्ण होने की प्रतीक्षा करता है।
type: docs
weight: 183
url: /hi/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) फ़ंक्शन

प्रदान किए गए [Task](../task/) ऑब्जेक्ट्स में से किसी एक के निष्पादन के पूर्ण होने की प्रतीक्षा करता है।

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | [Task](../task/) के उदाहरणों की एक एरे, जिस पर प्रतीक्षा की जाती है। |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | टास्क के पूर्ण होने तक प्रतीक्षा करते समय देखे जाने वाला [CancellationToken](../../system.threading/cancellationtoken/)। |

### रिटर्न वैल्यू

टास्क एरे में पूर्ण हुए टास्क का इंडेक्स।

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) फ़ंक्शन

प्रदान किए गए [Task](../task/) ऑब्जेक्ट्स में से किसी एक के निष्पादन के पूर्ण होने की प्रतीक्षा करता है।

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | [Task](../task/) के उदाहरणों की एक एरे, जिस पर प्रतीक्षा की जाती है। |

### रिटर्न वैल्यू

टास्क एरे में पूर्ण हुए टास्क का इंडेक्स।

## देखें

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* क्लास [CancellationToken](../../system.threading/cancellationtoken/)
* नेमस्पेस [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)