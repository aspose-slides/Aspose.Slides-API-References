---
title: Compare()
second_title: Aspose.Slides for C++ API संदर्भ
description: दो स्मार्ट पॉइंटर्स की तुलना करता है।
type: docs
weight: 1
url: /hi/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) function


दो स्मार्ट पॉइंटर्स की तुलना करता है।

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | पहले स्मार्ट पॉइंटर का प्रकार |
| U | दूसरे स्मार्ट पॉइंटर का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | पहला स्मार्ट पॉइंटर |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | दूसरा स्मार्ट पॉइंटर |

### वापसी मान

[Comparison](../../system/comparison/) परिणाम (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) function


दो अंकगणितीय मानों की तुलना करता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | अंकगणितीय प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const T\& | पहला मान |
| b | const T\& | दूसरा मान |

### वापसी मान

[Comparison](../../system/comparison/) परिणाम (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) function


एक स्मार्ट पॉइंटर की तुलना एक मान से करता है।

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | स्मार्ट पॉइंटर द्वारा इंगित प्रकार |
| U | मान का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | स्मार्ट पॉइंटर |
| b | const U\& | मान |

### वापसी मान

[Comparison](../../system/comparison/) परिणाम (0 if equal, -1 if a < b, 1 if a > b)

## देखें

* टाइपडिफ [SharedPtr](../../system/sharedptr/)
* नेमस्पेस [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)