---
title: Run()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए कतारबद्ध करता है और उस कार्य के लिए एक Task हैंडल लौटाता है।
type: docs
weight: 157
url: /hi/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) फ़ंक्शन

निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए कतारबद्ध करता है और उस कार्य के लिए एक [Task](../task/) हैंडल लौटाता है।

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | असिंक्रोनस रूप से निष्पादित करने हेतु कार्य। |

### रिटर्न वैल्यू

एक [Task](../task/) जो थ्रेड पूल में निष्पादित करने के लिए कतारबद्ध कार्य का प्रतिनिधित्व करता है।

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) फ़ंक्शन

निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए कतारबद्ध करता है और उस कार्य के लिए एक [Task](../task/) हैंडल लौटाता है।

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | असिंक्रोनस रूप से निष्पादित करने हेतु कार्य। |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | एक कैंसलेशन टोकन जो कार्य को रद्द करने के लिए उपयोग किया जा सकता है यदि वह अभी तक शुरू नहीं हुआ है। |

### रिटर्न वैल्यू

एक [Task](../task/) जो थ्रेड पूल में निष्पादित करने के लिए कतारबद्ध कार्य का प्रतिनिधित्व करता है।

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) फ़ंक्शन

निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए कतारबद्ध करता है और फ़ंक्शन द्वारा लौटाए गए [Task](../task/) के लिए एक प्रॉक्सी लौटाता है।

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | असिंक्रोनस रूप से निष्पादित होने वाला कार्य, जो एक [Task](../task/) लौटाता है। |

### रिटर्न वैल्यू

एक [Task](../task/) जो फ़ंक्शन द्वारा लौटाए गए [Task](../task/) के लिए प्रॉक्सी का प्रतिनिधित्व करता है।

## System::Threading::Tasks::Run(const Func\<TResult\>\&) फ़ंक्शन

निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए कतारबद्ध करता है और उस कार्य के लिए एक Task<TResult> हैंडल लौटाता है।

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TResult | टास्क द्वारा लौटाए गए परिणाम का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | असिंक्रोनस रूप से निष्पादित होने वाला कार्य। |

### रिटर्न वैल्यू

एक Task<TResult> जो थ्रेड पूल में निष्पादित करने के लिए कतारबद्ध कार्य का प्रतिनिधित्व करता है।

## देखें भी

* टाइपडिफ [TaskPtr](../../system/taskptr/)
* टाइपडिफ [Action](../../system/action/)
* टाइपडिफ [RTaskPtr](../../system/rtaskptr/)
* क्लास [CancellationToken](../../system.threading/cancellationtoken/)
* क्लास [Func](../../system/func/)
* नेमस्पेस [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)