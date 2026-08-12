---
title: Contains()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि क्या एक रीड-ओनली स्पैन में विशिष्ट मान मौजूद है।
type: docs
weight: 40
url: /hi/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) फ़ंक्शन

जाँचता है कि क्या एक रीड-ओनली स्पैन में विशिष्ट मान मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | वर्णन |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज के लिए स्पैन |
| value | const T\& | खोजने के लिए मान |

### वापसी मान

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) फ़ंक्शन

जाँचता है कि क्या एक म्यूटेबल स्पैन में विशिष्ट मान मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | वर्णन |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज के लिए म्यूटेबल स्पैन |
| value | const T\& | खोजने के लिए मान |

### वापसी मान

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) फ़ंक्शन

जाँचता है कि क्या एक कैरेक्टर स्पैन में निर्दिष्ट तुलना नियमों के साथ दूसरा कैरेक्टर स्पैन मौजूद है।

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | खोज के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | खोजने के लिए स्पैन |
| comparisonType | [StringComparison](../../system/stringcomparison/) | करने के लिए स्ट्रिंग तुलना का प्रकार |

### वापसी मान

true if value is found in span, false otherwise

## संबंधित देखें

* एन्यूम [StringComparison](../../system/stringcomparison/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)