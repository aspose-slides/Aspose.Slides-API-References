---
title: ResultTask()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक फ़ंक्शन के साथ ResultTask बनाता है जो एक मान लौटाता है।
type: docs
weight: 1
url: /hi/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) कंस्ट्रक्टर

एक [ResultTask](../) को एक फ़ंक्शन के साथ बनाता है जो एक मान लौटाता है।

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | एक फ़ंक्शन जिसे असिंक्रोनस रूप से निष्पादित किया जाता है और जो एक परिणाम लौटाता है |

## ResultTask::ResultTask() कंस्ट्रक्टर

आंतरिक कार्यान्वयन। उपयोगकर्ता कोड के लिए नहीं।

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## टिप्पणी

अनइनिशियलाइज़्ड परिणाम कार्यों को बनाने के लिए आंतरिक कंस्ट्रक्टर

## ResultTask::ResultTask(const T\&) कंस्ट्रक्टर

निर्दिष्ट परिणाम के साथ परिणाम कार्यों को बनाने के लिए आंतरिक कंस्ट्रक्टर।

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## देखें

* क्लास [Func](../../../system/func/)
* क्लास [ResultTask](../)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)