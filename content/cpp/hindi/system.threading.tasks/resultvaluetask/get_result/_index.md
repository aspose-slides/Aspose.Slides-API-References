---
title: get_Result()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: पूरा किए गए कार्य का परिणाम प्राप्त करता है।
type: docs
weight: 66
url: /hi/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() विधि

पूरा किए गए कार्य का परिणाम प्राप्त करता है।

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### रिटर्न मान

T परिणाम मान।

## टिप्पणियाँ

यदि कार्य ResultTask<T> द्वारा समर्थित है, तो यह विधि परिणाम की प्रतीक्षा करेगी और उसे कैश कर देगी। बाद में किए गए कॉल्स बिना प्रतीक्षा किए कैश किए हुए मान को लौटाएंगे।

## देखें

* क्लास [ResultValueTask](../)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)