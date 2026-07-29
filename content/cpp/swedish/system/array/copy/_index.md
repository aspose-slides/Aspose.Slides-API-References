---
title: Copy()
second_title: Aspose.Slides för C++ API-referens
description: Kopierar det angivna antalet element från källarrayen till destinationsarrayen.
type: docs
weight: 729
url: /sv/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

Kopierar det angivna antalet element från källarrayen till destinationsarrayen.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method

Kopierar det angivna antalet element från källarrayvyn till destinationsarrayen.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Source array view |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method

Kopierar det angivna antalet element från källarrayen till destinationsarrayvyn.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| dstArray | System::Details::ArrayView\<DstType\> | Destination array view |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method

Kopierar det angivna antalet element från källarrayvyn till destinationsarrayvyn.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Source array view |
| dstArray | System::Details::ArrayView\<DstType\> | Destination array view |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

Kopierar det angivna antalet element från källarrayen på stacken till destinationsarrayen.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Source array on stack |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method

Kopierar det angivna antalet element från källarrayen till destinationsarrayen på stacken.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Destination array on stack |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method

Kopierar det angivna antalet element från källarrayen på stacken till destinationsarrayen på stacken.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Source array on stack |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Destination array on stack |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Kopierar ett angivet antal element från källarrayen med start på den angivna indexen till den angivna positionen i destinationsarrayen.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| srcIndex | **int64_t** | [Index](../../index/) in the source array designating the beginning of the range of items to copy |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| dstIndex | **int64_t** | [Index](../../index/) in destination array to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Kopierar ett angivet antal element från källarrayvyn med start på den angivna indexen till den angivna positionen i destinationsarrayen.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Type of elements in source array view |
| DstType | Type of elements in destination array |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Source array view |
| srcIndex | **int64_t** | [Index](../../index/) in the source array view designating the beginning of the range of items to copy |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| dstIndex | **int64_t** | [Index](../../index/) in destination array to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

Kopierar ett angivet antal element från källarrayen med start på den angivna indexen till den angivna positionen i destinationsarrayvyn.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array view |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| srcIndex | **int64_t** | [Index](../../index/) in the source array designating the beginning of the range of items to copy |
| dstArray | System::Details::ArrayView\<DstType\> | Destination array view |
| dstIndex | **int64_t** | [Index](../../index/) in destination array view to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

Kopierar ett angivet antal element från källarrayvyn med start på den angivna indexen till den angivna positionen i destinationsarrayvyn.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Type of elements in source array view |
| DstType | Type of elements in destination array view |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Source array view |
| srcIndex | **int64_t** | [Index](../../index/) in the source array view designating the beginning of the range of items to copy |
| dstArray | System::Details::ArrayView\<DstType\> | Destination array view |
| dstIndex | **int64_t** | [Index](../../index/) in destination array view to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Kopierar ett angivet antal element från källarrayen på stacken med start på den angivna indexen till den angivna positionen i destinationsarrayen.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Type of elements in source array on stack |
| DstType | Type of elements in destination array |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Source array on stack |
| srcIndex | **int64_t** | [Index](../../index/) in the source array on stack designating the beginning of the range of items to copy |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| dstIndex | **int64_t** | [Index](../../index/) in destination array to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method

Kopierar ett angivet antal element från källarrayen med start på den angivna indexen till den angivna positionen i destinationsarrayen på stacken.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array on stack |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| srcIndex | **int64_t** | [Index](../../index/) in the source array designating the beginning of the range of items to copy |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Destination array on stack |
| dstIndex | **int64_t** | [Index](../../index/) in destination array on stack to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

Kopierar ett angivet antal element från källarrayen på stacken med start på den angivna indexen till den angivna positionen i destinationsarrayen på stacken.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Type of elements in source array on stack |
| DstType | Type of elements in destination array on stack |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Source array on stack |
| srcIndex | **int64_t** | [Index](../../index/) in the source array on stack designating the beginning of the range of items to copy |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Destination array on stack |
| dstIndex | **int64_t** | [Index](../../index/) in destination array on stack to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

Kopierar ett angivet antal element från källarrayvyn med start på den angivna indexen till den angivna positionen i destinationsarrayen på stacken.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| SrcType | Type of elements in source array on stack |
| DstType | Type of elements in destination array on stack |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Source array view |
| srcIndex | **int64_t** | [Index](../../index/) in the source array view designating the beginning of the range of items to copy |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Destination array on stack |
| dstIndex | **int64_t** | [Index](../../index/) in destination array on stack to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |

## Se även

* Typdef [ArrayPtr](../../arrayptr/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)