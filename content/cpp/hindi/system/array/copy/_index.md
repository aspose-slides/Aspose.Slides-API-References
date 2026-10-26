---
title: Copy()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट संख्या के तत्वों को स्रोत ऐरे से गंतव्य ऐरे में कॉपी करता है।
type: docs
weight: 729
url: /hi/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

निर्दिष्ट संख्या के तत्वों को स्रोत ऐरे से गंतव्य ऐरे में कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | स्रोत ऐरे |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method

निर्दिष्ट संख्या के तत्वों को स्रोत ऐरे व्यू से गंतव्य ऐरे में कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | स्रोत ऐरे व्यू |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method

निर्दिष्ट संख्या के तत्वों को स्रोत ऐरे से गंतव्य ऐरे व्यू में कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | स्रोत ऐरे |
| dstArray | System::Details::ArrayView\<DstType\> | गंतव्य ऐरे व्यू |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method

निर्दिष्ट संख्या के तत्वों को स्रोत ऐरे व्यू से गंतव्य ऐरे व्यू में कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | स्रोत ऐरे व्यू |
| dstArray | System::Details::ArrayView\<DstType\> | गंतव्य ऐरे व्यू |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

निर्दिष्ट संख्या के तत्वों को स्टैक पर स्थित स्रोत ऐरे से गंतव्य ऐरे में कॉपी करता है।

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | स्टैक पर स्थित स्रोत ऐरे |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method

निर्दिष्ट संख्या के तत्वों को स्रोत ऐरे से स्टैक पर स्थित गंतव्य ऐरे में कॉपी करता है।

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | स्रोत ऐरे |
| dstArray | System::Details::StackArray\<DstType, N\>\& | स्टैक पर स्थित गंतव्य ऐरे |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method

निर्दिष्ट संख्या के तत्वों को स्टैक पर स्थित स्रोत ऐरे से स्टैक पर स्थित गंतव्य ऐरे में कॉपी करता है।

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | स्टैक पर स्थित स्रोत ऐरे |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | स्टैक पर स्थित गंतव्य ऐरे |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

निर्दिष्ट सूचकांक से शुरू होते स्रोत ऐरे से निर्दिष्ट संख्या के तत्वों को गंतव्य ऐरे में निर्दिष्ट स्थिति तक कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्रोत ऐरे में तत्वों का प्रकार |
| DstType | गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | स्रोत ऐरे |
| srcIndex | **int64_t** | [Index](../../index/) स्रोत ऐरे में कॉपी किए जाने वाले आइटमों की रेंज की शुरुआत को दर्शाता है |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे में कॉपी किए गए आइटमों को सम्मिलित करने की प्रारंभिक स्थिति को दर्शाता है |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

निर्दिष्ट सूचकांक से शुरू होते स्रोत ऐरे व्यू से निर्दिष्ट संख्या के तत्वों को गंतव्य ऐरे में निर्दिष्ट स्थिति तक कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्रोत ऐरे व्यू में तत्वों का प्रकार |
| DstType | गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | स्रोत ऐरे व्यू |
| srcIndex | **int64_t** | [Index](../../index/) स्रोत ऐरे व्यू में कॉपी किए जाने वाले आइटमों की रेंज की शुरुआत को दर्शाता है |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे में कॉपी किए गए आइटमों को सम्मिलित करने की प्रारंभिक स्थिति को दर्शाता है |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

निर्दिष्ट सूचकांक से शुरू होते स्रोत ऐरे से निर्दिष्ट संख्या के तत्वों को गंतव्य ऐरे व्यू में निर्दिष्ट स्थिति तक कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्रोत ऐरे में तत्वों का प्रकार |
| DstType | गंतव्य ऐरे व्यू में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | स्रोत ऐरे |
| srcIndex | **int64_t** | [Index](../../index/) स्रोत ऐरे में कॉपी किए जाने वाले आइटमों की रेंज की शुरुआत को दर्शाता है |
| dstArray | System::Details::ArrayView\<DstType\> | गंतव्य ऐरे व्यू |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे व्यू में कॉपी किए गए आइटमों को सम्मिलित करने की प्रारंभिक स्थिति को दर्शाता है |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

निर्दिष्ट सूचकांक से शुरू होते स्रोत ऐरे व्यू से निर्दिष्ट संख्या के तत्वों को गंतव्य ऐरे व्यू में निर्दिष्ट स्थिति तक कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्रोत ऐरे व्यू में तत्वों का प्रकार |
| DstType | गंतव्य ऐरे व्यू में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | स्रोत ऐरे व्यू |
| srcIndex | **int64_t** | [Index](../../index/) स्रोत ऐरे व्यू में कॉपी किए जाने वाले आइटमों की रेंज की शुरुआत को दर्शाता है |
| dstArray | System::Details::ArrayView\<DstType\> | गंतव्य ऐरे व्यू |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे व्यू में कॉपी किए गए आइटमों को सम्मिलित करने की प्रारंभिक स्थिति को दर्शाता है |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

निर्दिष्ट सूचकांक से शुरू होते स्टैक पर स्थित स्रोत ऐरे से निर्दिष्ट संख्या के तत्वों को गंतव्य ऐरे में निर्दिष्ट स्थिति तक कॉपी करता है।

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्टैक पर स्थित स्रोत ऐरे में तत्वों का प्रकार |
| DstType | गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | स्टैक पर स्थित स्रोत ऐरे |
| srcIndex | **int64_t** | [Index](../../index/) स्टैक पर स्थित स्रोत ऐरे में कॉपी किए जाने वाले आइटमों की रेंज की शुरुआत को दर्शाता है |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| dstIndex | **int64_t** | [Index](../../index/) गंतव्य ऐरे में कॉपी किए गए आइटमों को सम्मिलित करने की प्रारंभिक स्थिति को दर्शाता है |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method

निर्दिष्ट सूचकांक से शुरू होते स्रोत ऐरे से स्टैक पर स्थित गंतव्य ऐरे में निर्दिष्ट संख्या के तत्वों को कॉपी करता है।

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्रोत ऐरे में तत्वों का प्रकार |
| DstType | स्टैक पर स्थित गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | स्रोत ऐरे |
| srcIndex | **int64_t** | [Index](../../index/) स्रोत ऐरे में कॉपी किए जाने वाले आइटमों की रेंज की शुरुआत को दर्शाता है |
| dstArray | System::Details::StackArray\<DstType, N\>\& | स्टैक पर स्थित गंतव्य ऐरे |
| dstIndex | **int64_t** | [Index](../../index/) स्टैक पर स्थित गंतव्य ऐरे में कॉपी किए गए आइटमों को सम्मिलित करने की प्रारंभिक स्थिति को दर्शाता है |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

निर्दिष्ट सूचकांक से शुरू होते स्टैक पर स्थित स्रोत ऐरे से स्टैक पर स्थित गंतव्य ऐरे में निर्दिष्ट संख्या के तत्वों को कॉपी करता है।

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्टैक पर स्थित स्रोत ऐरे में तत्वों का प्रकार |
| DstType | स्टैक पर स्थित गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | स्टैक पर स्थित स्रोत ऐरे |
| srcIndex | **int64_t** | [Index](../../index/) स्टैक पर स्थित स्रोत ऐरे में कॉपी किए जाने वाले आइटमों की रेंज की शुरुआत को दर्शाता है |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | स्टैक पर स्थित गंतव्य ऐरे |
| dstIndex | **int64_t** | [Index](../../index/) स्टैक पर स्थित गंतव्य ऐरे में कॉपी किए गए आइटमों को सम्मिलित करने की प्रारंभिक स्थिति को दर्शाता है |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

निर्दिष्ट सूचकांक से शुरू होते स्रोत ऐरे व्यू से स्टैक पर स्थित गंतव्य ऐरे में निर्दिष्ट संख्या के तत्वों को कॉपी करता है।

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्टैक पर स्थित स्रोत ऐरे में तत्वों का प्रकार |
| DstType | स्टैक पर स्थित गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | स्रोत ऐरे व्यू |
| srcIndex | **int64_t** | [Index](../../index/) स्रोत ऐरे व्यू में कॉपी किए जाने वाले आइटमों की रेंज की शुरुआत को दर्शाता है |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | स्टैक पर स्थित गंतव्य ऐरे |
| dstIndex | **int64_t** | [Index](../../index/) स्टैक पर स्थित गंतव्य ऐरे में कॉपी किए गए आइटमों को सम्मिलित करने की प्रारंभिक स्थिति को दर्शाता है |
| count | **int64_t** | कॉपी करने के तत्वों की संख्या |

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)