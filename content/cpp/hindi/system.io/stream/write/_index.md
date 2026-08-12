---
title: Write()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स के उप-रेंज को स्ट्रीम में लिखता है।
type: docs
weight: 53
url: /hi/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) मेथड

निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स के उप-रेंज को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाला एरे |
| offset | **int32_t** | **buffer** में वह 0-आधारित इंडेक्स जहाँ से उप-रेंज लिखना शुरू होता है |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) मेथड

निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स के उप-रेंज को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | लिखने के लिए बाइट्स वाली एरे व्यू |
| offset | **int32_t** | **buffer** में वह 0-आधारित इंडेक्स जहाँ से उप-रेंज लिखना शुरू होता है |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) मेथड

निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स के उप-रेंज को स्ट्रीम में लिखता है।

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| N | स्टैक एरे का आकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | लिखने के लिए बाइट्स वाला स्टैक एरे |
| offset | **int32_t** | **buffer** में वह 0-आधारित इंडेक्स जहाँ से उप-रेंज लिखना शुरू होता है |
| count | **int32_t** | लिखने के लिए उप-रेंज में तत्वों की संख्या |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) मेथड

निर्दिष्ट बाइट स्पैन से निर्दिष्ट बाइट्स के उप-रेंज को स्ट्रीम में लिखता है।

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | लिखे गए बाइट्स को पढ़ने के लिए बाइट स्पैन |

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)