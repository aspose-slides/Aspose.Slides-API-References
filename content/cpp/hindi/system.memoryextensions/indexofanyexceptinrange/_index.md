---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API संदर्भ
description: ReadOnlySpan<T> में निर्दिष्ट रेंज से बाहर पहले तत्व का सूचकांक खोजता है
type: docs
weight: 183
url: /hi/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) फ़ंक्शन


ReadOnlySpan<T> में निर्दिष्ट रेंज से बाहर पहले तत्व का सूचकांक खोजता है

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जिस स्पैन में खोज करनी है |
| lowInclusive | const T\& | रेंज का निम्न सीमा (समावेशी) |
| highInclusive | const T\& | रेंज का उच्च सीमा (समावेशी) |

### रिटर्न वैल्यू

रेंज के बाहर पहले तत्व का शून्य-आधारित सूचकांक, या यदि न मिले तो -1

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) फ़ंक्शन


Span<T> में निर्दिष्ट रेंज से बाहर पहले तत्व का सूचकांक खोजता है

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जिस स्पैन में खोज करनी है |
| lowInclusive | const T\& | रेंज का निम्न सीमा (समावेशी) |
| highInclusive | const T\& | रेंज का उच्च सीमा (समावेशी) |

### रिटर्न वैल्यू

रेंज के बाहर पहले तत्व का शून्य-आधारित सूचकांक, या यदि न मिले तो -1

## देखें

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)