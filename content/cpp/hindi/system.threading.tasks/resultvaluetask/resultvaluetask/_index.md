---
title: ResultValueTask()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक खाली, अनइनिशियलाइज़्ड ResultValueTask बनाता है।
type: docs
weight: 1
url: /hi/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() कन्स्ट्रक्टर


खाली, अनइनिशियलाइज़्ड [ResultValueTask](../) बनाता है।

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## टिप्पणी



टास्क पूरा नहीं हुआ है और इसमें कोई परिणाम नहीं है। परिणाम प्राप्त करने का प्रयत्न करने पर अपवाद फेंका जाएगा। 

## ResultValueTask::ResultValueTask(const T\&) कन्स्ट्रक्टर


निर्दिष्ट परिणाम के साथ एक पूरा [ResultValueTask](../) बनाता है।

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| result | const T\& | एक पूर्ण टास्क में लपेटे जाने वाला परिणाम मान। |
## टिप्पणी



यह एक सफलतापूर्वक पूर्ण टास्क बनाता है जो तुरंत मान लौटाता है। 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) कन्स्ट्रक्टर


ResultTask<T> के साझा पॉइंटर से एक [ResultValueTask](../) बनाता है।

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | लपेटने के लिये टास्क। खाली टास्क के लिये null हो सकता है। |
## टिप्पणी



[ResultValueTask](../) प्रदान किए गए टास्क की स्थिति और परिणाम दर्शाएगा। 

## साथ ही देखें

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)