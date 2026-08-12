---
title: CopyTo()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऐरे के सभी तत्वों को निर्दिष्ट गंतव्य ऐरे में कॉपी करता है। तत्वों को गंतव्य ऐरे में arrayIndex तर्क द्वारा निर्दिष्ट सूचकांक से शुरू करके डाला जाता है।
type: docs
weight: 118
url: /hi/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) विधि

वर्तमान ऐरे के सभी तत्वों को निर्दिष्ट गंतव्य ऐरे में कॉपी करता है। तत्वों को गंतव्य ऐरे में arrayIndex तर्क द्वारा निर्दिष्ट सूचकांक से शुरू करके डाला जाता है।

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | गंतव्य ऐरे |
| arrayIndex | int | [Index](../../index/) गंतव्य ऐरे में कॉपी किए गए आइटम सम्मिलित करने के लिए शुरू करने का सूचकांक |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const विधि

वर्तमान ऐरे के सभी तत्वों को निर्दिष्ट गंतव्य ऐरे में कॉपी करता है। तत्वों को गंतव्य ऐरे में dstIndex तर्क द्वारा निर्दिष्ट सूचकांक से शुरू करके डाला जाता है।

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| DstType | गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे में कॉपी किए गए आइटम सम्मिलित करने के लिए शुरू करने का सूचकांक |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const विधि

वर्तमान ऐरे के सभी तत्वों को निर्दिष्ट गंतव्य ऐरे दृश्य में कॉपी करता है। तत्वों को गंतव्य ऐरे दृश्य में dstIndex तर्क द्वारा निर्दिष्ट सूचकांक से शुरू करके डाला जाता है।

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| DstType | गंतव्य ऐरे दृश्य में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | गंतव्य ऐरे दृश्य |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे दृश्य में कॉपी किए गए आइटम सम्मिलित करने के लिए शुरू करने का सूचकांक |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const विधि

वर्तमान ऐरे से निर्दिष्ट स्थिति से शुरू करके निर्दिष्ट संख्या के तत्वों को निर्दिष्ट गंतव्य ऐरे में कॉपी करता है। तत्वों को गंतव्य ऐरे में dstIndex तर्क द्वारा निर्दिष्ट सूचकांक से शुरू करके डाला जाता है।

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| DstType | गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| srcIndex | **int64_t** | [Index](../../index/) स्रोत ऐरे में कॉपी करना शुरू करने के लिए सूचकांक |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे में कॉपी किए गए आइटम सम्मिलित करने के लिए शुरू करने का सूचकांक |
| count | **int64_t** | कॉपी करने के लिए तत्वों की संख्या |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const विधि

वर्तमान ऐरे से निर्दिष्ट स्थिति से शुरू करके निर्दिष्ट संख्या के तत्वों को निर्दिष्ट गंतव्य ऐरे दृश्य में कॉपी करता है। तत्वों को गंतव्य ऐरे दृश्य में dstIndex तर्क द्वारा निर्दिष्ट सूचकांक से शुरू करके डाला जाता है।

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| DstType | गंतव्य ऐरे दृश्य में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | गंतव्य ऐरे दृश्य |
| srcIndex | **int64_t** | [Index](../../index/) स्रोत ऐरे में कॉपी करना शुरू करने के लिए सूचकांक |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे दृश्य में कॉपी किए गए आइटम सम्मिलित करने के लिए शुरू करने का सूचकांक |
| count | **int64_t** | कॉपी करने के लिए तत्वों की संख्या |

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* क्लास [Array](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)