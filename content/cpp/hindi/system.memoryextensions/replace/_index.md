---
title: Replace()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: Span में किसी मान की सभी घटनाओं को नए मान से बदलता है।
type: docs
weight: 287
url: /hi/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

एक [Span](../../system/span/) में किसी मान की सभी घटनाओं को नए मान से बदलता है।

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | इन-स्थान पर संशोधित करने के लिए स्पैन |
| oldValue | const T\& | खोजने और बदलने के लिए मान |
| newValue | const T\& | oldValue को बदलने के लिए नया मान |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

स्रोत से गंतव्य में तत्वों की प्रतिलिपि बनाता है, प्रतिलिपि के दौरान निर्दिष्ट मानों को बदलते हुए।

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | कॉपी करने के लिए स्रोत [ReadOnlySpan](../../system/readonlyspan/) |
| destination | [Span](../../system/span/)\<T\>\& | कॉपी करने के लिए गंतव्य [Span](../../system/span/) |
| oldValue | const T\& | खोजने और बदलने के लिए मान |
| newValue | const T\& | oldValue को बदलने के लिए नया मान |

## संबंधित देखें

* क्लास [Span](../../system/span/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)