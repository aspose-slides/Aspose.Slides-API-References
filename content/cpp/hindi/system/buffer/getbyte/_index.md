---
title: GetByte()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट टाइप्ड एरे को कच्चे बाइट एरे के रूप में व्याख्या करता है और निर्दिष्ट बाइट ऑफसेट पर बाइट मान प्राप्त करता है।
type: docs
weight: 27
url: /hi/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) विधि


निर्दिष्ट टाइप्ड एरे को कच्चे बाइट एरे के रूप में व्याख्या करता है और निर्दिष्ट बाइट ऑफसेट पर बाइट मान प्राप्त करता है।

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | एरे के तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | लक्ष्य एरे |
| index | int | बाइट को प्राप्त करने का शून्य-आधारित ऑफसेट |

### रिटर्न मान

निर्दिष्ट सूचकांक पर बाइट मान

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) विधि


निर्दिष्ट टाइप्ड एरे को कच्चे बाइट एरे के रूप में व्याख्या करता है और निर्दिष्ट बाइट ऑफसेट पर बाइट मान प्राप्त करता है।

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | एरे व्यू के तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | लक्ष्य एरे व्यू |
| index | int | बाइट को प्राप्त करने का शून्य-आधारित ऑफसेट |

### रिटर्न मान

निर्दिष्ट सूचकांक पर बाइट मान

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) विधि


निर्दिष्ट टाइप्ड एरे को कच्चे बाइट एरे के रूप में व्याख्या करता है और निर्दिष्ट बाइट ऑफसेट पर बाइट मान प्राप्त करता है।

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्टैक एरे के तत्वों का प्रकार |
| N | स्टैक एरे का आकार |

### आर्ग्युमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | लक्ष्य स्टैक एरे |
| index | int | बाइट को प्राप्त करने का शून्य-आधारित ऑफसेट |

### रिटर्न मान

निर्दिष्ट सूचकांक पर बाइट मान

## संबंधित देखें

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [Array](../../array/)
* क्लास [Buffer](../)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)