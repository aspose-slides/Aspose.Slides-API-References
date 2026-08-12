---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित रेंज के बाहर किसी भी तत्व की अंतिम उपस्थिति को एक स्पैन के भीतर खोजता है।
type: docs
weight: 248
url: /hi/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) फ़ंक्शन

किसी स्पैन में निर्दिष्ट रेंज के बाहर किसी भी तत्व की अंतिम उपस्थिति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए स्पैन |
| lowInclusive | const T\& | रेंज की निचली सीमा (समावेशी) |
| highInclusive | const T\& | रेंज की ऊपरी सीमा (समावेशी) |

### रिटर्न वैल्यू

रेंज के बाहर अंतिम तत्व का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

किसी परिवर्तनशील स्पैन में निर्दिष्ट रेंज के बाहर किसी भी तत्व की अंतिम उपस्थिति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोजने के लिए स्पैन |
| lowInclusive | const T\& | रेंज की निचली सीमा (समावेशी) |
| highInclusive | const T\& | रेंज की ऊपरी सीमा (समावेशी) |

### रिटर्न वैल्यू

रेंज के बाहर अंतिम तत्व का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## संबंधित देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)