---
title: BlockCopy()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट संख्या में बाइट्स को स्रोत बफ़र से गंतव्य बफ़र में कॉपी करता है।
type: docs
weight: 1
url: /hi/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) विधि


स्रोत बफ़र से गंतव्य बफ़र में निर्दिष्ट संख्या में बाइट्स की प्रतिलिपि बनाता है।

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const **uint8_t** * | स्रोत बफ़र की पॉइंटर |
| srcOffset | int | स्रोत बफ़र में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | **uint8_t** * | गंतव्य बफ़र की पॉइंटर |
| dstOffset | int | गंतव्य बफ़र में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) विधि


दो निर्दिष्ट टाइप्ड एरेज़ को बाइट्स की कच्ची एरेज़ के रूप में व्याख्या करता है और एक से दूसरे में डेटा की प्रतिलिपि बनाता है।

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSrc | स्रोत एरे के तत्वों का प्रकार |
| TDst | गंतव्य एरे के तत्वों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | स्रोत एरे |
| srcOffset | int | स्रोत एरे में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | गंतव्य एरे |
| dstOffset | int | गंतव्य एरे में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) विधि


दो निर्दिष्ट एरेज़ को बाइट्स की कच्ची एरेज़ के रूप में व्याख्या करता है और एक से दूसरे में डेटा की प्रतिलिपि बनाता है।

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | स्रोत एरे |
| srcOffset | int | स्रोत एरे में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | गंतव्य एरे |
| dstOffset | int | गंतव्य एरे में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) विधि


दो निर्दिष्ट टाइप्ड एरेज़ को बाइट्स की कच्ची एरेज़ के रूप में व्याख्या करता है और उनके बीच डेटा की प्रतिलिपि बनाता है।

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSrc | स्रोत एरे व्यू के तत्वों का प्रकार |
| TDst | गंतव्य एरे व्यू के तत्वों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | स्रोत एरे व्यू |
| srcOffset | int | स्रोत एरे व्यू में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | const System::Details::ArrayView\<TDst\>\& | गंतव्य एरे व्यू |
| dstOffset | int | गंतव्य एरे व्यू में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) विधि


दो निर्दिष्ट टाइप्ड एरेज़ को बाइट्स की कच्ची एरेज़ के रूप में व्याख्या करता है और एक से दूसरे में डेटा की प्रतिलिपि बनाता है।

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSrc | स्रोत एरे के तत्वों का प्रकार |
| TDst | गंतव्य एरे व्यू के तत्वों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | स्रोत एरे |
| srcOffset | int | स्रोत एरे में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | const System::Details::ArrayView\<TDst\>\& | गंतव्य एरे व्यू |
| dstOffset | int | गंतव्य एरे व्यू में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) विधि


दो निर्दिष्ट टाइप्ड एरेज़ को बाइट्स की कच्ची एरेज़ के रूप में व्याख्या करता है और एक से दूसरे में डेटा की प्रतिलिपि बनाता है।

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSrc | स्रोत एरे व्यू के तत्वों का प्रकार |
| TDst | गंतव्य एरे के तत्वों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | स्रोत एरे व्यू |
| srcOffset | int | स्रोत एरे व्यू में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | गंतव्य एरे |
| dstOffset | int | गंतव्य एरे में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) विधि


दो निर्दिष्ट टाइप्ड एरेज़ को बाइट्स की कच्ची एरेज़ के रूप में व्याख्या करता है और एक से दूसरे में डेटा की प्रतिलिपि बनाता है।

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSrc | स्रोत स्टैक एरे के तत्वों का प्रकार |
| NS | स्रोत स्टैक एरे का आकार |
| TDst | गंतव्य स्टैक एरे के तत्वों का प्रकार |
| ND | गंतव्य स्टैक एरे का आकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | स्रोत स्टैक एरे |
| srcOffset | int | स्रोत स्टैक एरे में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | const System::Details::StackArray\<TDst, ND\>\& | गंतव्य स्टैक एरे |
| dstOffset | int | गंतव्य स्टैक एरे में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) विधि


दो निर्दिष्ट टाइप्ड एरेज़ को बाइट्स की कच्ची एरेज़ के रूप में व्याख्या करता है और एक से दूसरे में डेटा की प्रतिलिपि बनाता है।

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSrc | स्रोत एरे के तत्वों का प्रकार |
| TDst | गंतव्य स्टैक एरे के तत्वों का प्रकार |
| ND | गंतव्य स्टैक एरे का आकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | स्रोत एरे |
| srcOffset | int | स्रोत एरे में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | const System::Details::StackArray\<TDst, ND\>\& | गंतव्य स्टैक एरे |
| dstOffset | int | गंतव्य स्टैक एरे में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) विधि


दो निर्दिष्ट टाइप्ड एरेज़ को बाइट्स की कच्ची एरेज़ के रूप में व्याख्या करता है और एक से दूसरे में डेटा की प्रतिलिपि बनाता है।

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSrc | स्रोत स्टैक एरे के तत्वों का प्रकार |
| NS | स्रोत स्टैक एरे का आकार |
| TDst | गंतव्य एरे के तत्वों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | स्रोत स्टैक एरे |
| srcOffset | int | स्रोत स्टैक एरे में वह बाइट ऑफ़सेट जहाँ से प्रतिलिपि शुरू होती है |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | गंतव्य एरे |
| dstOffset | int | गंतव्य एरे में वह बाइट ऑफ़सेट जहाँ डेटा डालना शुरू किया जाता है |
| count | int | प्रतिलिपि किए जाने वाले बाइट्स की संख्या |

## संबंधित देखें

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [Buffer](../)
* क्लास [Array](../../array/)
* क्लास [ArrayBase](../../arraybase/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)