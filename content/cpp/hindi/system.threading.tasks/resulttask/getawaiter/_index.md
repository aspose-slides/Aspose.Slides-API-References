---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API संदर्भ
description: Await के साथ उपयोग के लिए इस result task के लिए एक awaiter प्राप्त करता है।
type: docs
weight: 53
url: /hi/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const मेथड


Await के साथ उपयोग के लिए इस ResultTask के लिए एक awaiter प्राप्त करता है।

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### रिटर्न वैल्यू

Runtime::CompilerServices::ResultTaskAwaiter<T> एक awaiter इंस्टेंस जो परिणाम लौटाता है
## टिप्पणी



जब await किया जाता है, तो coroutine परिणाम मान उपलब्ध होने के साथ पुनः प्रारम्भ होगा 

## देखें

* क्लास [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* क्लास [ResultTask](../)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)