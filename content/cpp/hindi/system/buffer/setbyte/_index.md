---
title: SetByte()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट प्रकार के एरे को एक कच्चे बाइट एरे के रूप में व्याख्यायित करता है और निर्दिष्ट बाइट मान को निर्दिष्ट बाइट ऑफसेट पर सेट करता है।
type: docs
weight: 40
url: /hi/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) विधि

निर्दिष्ट प्रकार के एरे को एक कच्चे बाइट एरे के रूप में व्याख्यायित करता है और निर्दिष्ट बाइट मान को निर्दिष्ट बाइट ऑफसेट पर सेट करता है।

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | एरे के तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | लक्ष्य एरे |
| index | int | सेट करने के लिए बाइट का शून्य-आधारित ऑफसेट |
| value | **uint8_t** | सेट करने के लिए बाइट मान |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) विधि

निर्दिष्ट प्रकार के एरे को एक कच्चे बाइट एरे के रूप में व्याख्यायित करता है और निर्दिष्ट बाइट मान को निर्दिष्ट बाइट ऑफसेट पर सेट करता है।

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | एरे के तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | लक्ष्य एरे व्यू |
| index | int | सेट करने के लिए बाइट का शून्य-आधारित ऑफसेट |
| value | **uint8_t** | सेट करने के लिए बाइट मान |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) विधि

निर्दिष्ट प्रकार के एरे को एक कच्चे बाइट एरे के रूप में व्याख्यायित करता है और निर्दिष्ट बाइट मान को निर्दिष्ट बाइट ऑफसेट पर सेट करता है।

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | एरे के तत्वों का प्रकार |
| N | स्टैक एरे का आकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | लक्ष्य स्टैक एरे |
| index | int | सेट करने के लिए बाइट का शून्य-आधारित ऑफसेट |
| value | **uint8_t** | सेट करने के लिए बाइट मान |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)