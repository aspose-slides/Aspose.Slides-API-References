---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट रेंज के भीतर किसी भी तत्व की स्पैन में आखिरी उपस्थिति ढूँढता है।
type: docs
weight: 261
url: /hi/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) फ़ंक्शन

स्पैन के भीतर निर्दिष्ट रेंज में किसी भी तत्व की आखिरी उपस्थिति खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जिस स्पैन में खोज करनी है |
| lowInclusive | const T\& | रेंज की निचली सीमा (शामिल) |
| highInclusive | const T\& | रेंज की ऊपरी सीमा (शामिल) |

### रिटर्न वैल्यू

रेंज के भीतर अंतिम तत्व का शून्य-आधारित इंडेक्स, या यदि न मिले तो -1

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

म्यूटेबल स्पैन के भीतर निर्दिष्ट रेंज में किसी भी तत्व की आखिरी उपस्थिति खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जिस स्पैन में खोज करनी है |
| lowInclusive | const T\& | रेंज की निचली सीमा (शामिल) |
| highInclusive | const T\& | रेंज की ऊपरी सीमा (शामिल) |

### रिटर्न वैल्यू

रेंज के भीतर अंतिम तत्व का शून्य-आधारित इंडेक्स, या यदि न मिले तो -1

## देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नामस्थान [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)