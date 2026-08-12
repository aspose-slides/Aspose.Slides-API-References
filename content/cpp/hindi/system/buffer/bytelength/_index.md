---
title: ByteLength()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट एरे के सभी तत्वों द्वारा कब्जे में ली गई बाइट्स की संख्या निर्धारित करता है।
type: docs
weight: 14
url: /hi/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) विधि

निर्दिष्ट एरे के सभी तत्वों द्वारा कब्जे में ली गई बाइट्स की संख्या निर्धारित करता है।

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | एरे के तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | एक एरे |

### रिटर्न वैल्यू

निर्दिष्ट एरे के सभी तत्वों द्वारा कब्जे में ली गई बाइट्स की संख्या

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) विधि

निर्दिष्ट एरे के सभी तत्वों द्वारा कब्जे में ली गई बाइट्स की संख्या निर्धारित करता है।

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | एरे व्यू के तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | एक एरे व्यू |

### रिटर्न वैल्यू

निर्दिष्ट एरे व्यू के सभी तत्वों द्वारा कब्जे में ली गई बाइट्स की संख्या

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) विधि

निर्दिष्ट एरे के सभी तत्वों द्वारा कब्जे में ली गई बाइट्स की संख्या निर्धारित करता है।

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्टैक एरे के तत्वों का प्रकार |
| N | स्टैक एरे का आकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | एक स्टैक एरे |

### रिटर्न वैल्यू

निर्दिष्ट स्टैक एरे के सभी तत्वों द्वारा कब्जे में ली गई बाइट्स की संख्या

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../sharedptr/)
* क्लास [Array](../../array/)
* क्लास [Buffer](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)