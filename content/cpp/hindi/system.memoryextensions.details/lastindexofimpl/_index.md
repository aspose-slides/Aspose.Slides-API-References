---
title: LastIndexOfImpl()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्पैन में मान का अंतिम अनुक्रमणिका खोजता है।
type: docs
weight: 14
url: /hi/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) फ़ंक्शन

एक स्पैन में मान का अंतिम अनुक्रमणिका खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) खोजने के लिए |
| length | **int32_t** | खोज के भीतर लंबाई |
| value | const T\& | खोजने के लिये मान |

### रिटर्न वैल्यू

मान का अंतिम अनुक्रमणिका, या यदि न मिला तो -1

## देखें भी

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* नेमस्पेस [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)