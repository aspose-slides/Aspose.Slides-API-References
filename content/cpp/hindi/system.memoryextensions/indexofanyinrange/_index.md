---
title: IndexOfAnyInRange()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ReadOnlySpan<T> में निर्दिष्ट रेंज के भीतर पहले तत्व का इंडेक्स ढूँढ़ता है
type: docs
weight: 196
url: /hi/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) फ़ंक्शन

निर्दिष्ट रेंज में पहले तत्व का इंडेक्स खोजता है जो ReadOnlySpan<T> में स्थित है

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज करने वाला स्पैन |
| lowInclusive | const T\& | रेंज की निचली सीमा (समावेशी) |
| highInclusive | const T\& | रेंज की ऊपरी सीमा (समावेशी) |

### रिटर्न वैल्यू

रेंज के भीतर पहले तत्व का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

निर्दिष्ट रेंज में पहले तत्व का इंडेक्स खोजता है जो Span<T> में स्थित है

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज करने वाला स्पैन |
| lowInclusive | const T\& | रेंज की निचली सीमा (समावेशी) |
| highInclusive | const T\& | रेंज की ऊपरी सीमा (समावेशी) |

### रिटर्न वैल्यू

रेंज के भीतर पहले तत्व का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## See Also

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नामस्थान [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)