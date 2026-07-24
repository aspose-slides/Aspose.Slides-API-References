---
title: Copy()
second_title: Aspose.Slides für C++ API-Referenz
description: Kopiert die angegebene Anzahl von Elementen vom Quell-Array zum Ziel-Array.
type: docs
weight: 729
url: /de/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

Kopiert die angegebene Anzahl von Elementen vom Quell-Array zum Ziel-Array.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Quell-Array |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Ziel-Array |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method

Kopiert die angegebene Anzahl von Elementen von der Quell-Array-Ansicht zum Ziel-Array.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Quell-Array-Ansicht |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Ziel-Array |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method

Kopiert die angegebene Anzahl von Elementen vom Quell-Array zur Ziel-Array-Ansicht.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Quell-Array |
| dstArray | System::Details::ArrayView\<DstType\> | Ziel-Array-Ansicht |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method

Kopiert die angegebene Anzahl von Elementen von der Quell-Array-Ansicht zur Ziel-Array-Ansicht.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Quell-Array-Ansicht |
| dstArray | System::Details::ArrayView\<DstType\> | Ziel-Array-Ansicht |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

Kopiert die angegebene Anzahl von Elementen vom Quell-Array im Stack zum Ziel-Array.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Quell-Array im Stack |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Ziel-Array |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method

Kopiert die angegebene Anzahl von Elementen vom Quell-Array zum Ziel-Array im Stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Quell-Array |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Ziel-Array im Stack |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method

Kopiert die angegebene Anzahl von Elementen vom Quell-Array im Stack zum Ziel-Array im Stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Quell-Array im Stack |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Ziel-Array im Stack |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Kopiert eine angegebene Anzahl von Elementen vom Quell-Array, beginnend am angegebenen Index, an die angegebene Position im Ziel-Array.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quell-Array |
| DstType | Typ der Elemente im Ziel-Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Quell-Array |
| srcIndex | **int64_t** | [Index](../../index/) im Quell-Array, das den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Ziel-Array |
| dstIndex | **int64_t** | [Index](../../index/) im Ziel-Array, an dem die kopierten Elemente eingefügt werden sollen |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Kopiert eine angegebene Anzahl von Elementen von der Quell-Array-Ansicht, beginnend am angegebenen Index, an die angegebene Position im Ziel-Array.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente in der Quell-Array-Ansicht |
| DstType | Typ der Elemente im Ziel-Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Quell-Array-Ansicht |
| srcIndex | **int64_t** | [Index](../../index/) in der Quell-Array-Ansicht, das den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Ziel-Array |
| dstIndex | **int64_t** | [Index](../../index/) im Ziel-Array, an dem die kopierten Elemente eingefügt werden sollen |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

Kopiert eine angegebene Anzahl von Elementen vom Quell-Array, beginnend am angegebenen Index, an die angegebene Position in der Ziel-Array-Ansicht.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quell-Array |
| DstType | Typ der Elemente in der Ziel-Array-Ansicht |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Quell-Array |
| srcIndex | **int64_t** | [Index](../../index/) im Quell-Array, das den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | System::Details::ArrayView\<DstType\> | Ziel-Array-Ansicht |
| dstIndex | **int64_t** | [Index](../../index/) in der Ziel-Array-Ansicht, an dem die kopierten Elemente eingefügt werden sollen |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

Kopiert eine angegebene Anzahl von Elementen von der Quell-Array-Ansicht, beginnend am angegebenen Index, an die angegebene Position in der Ziel-Array-Ansicht.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente in der Quell-Array-Ansicht |
| DstType | Typ der Elemente in der Ziel-Array-Ansicht |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Quell-Array-Ansicht |
| srcIndex | **int64_t** | [Index](../../index/) in der Quell-Array-Ansicht, das den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | System::Details::ArrayView\<DstType\> | Ziel-Array-Ansicht |
| dstIndex | **int64_t** | [Index](../../index/) in der Ziel-Array-Ansicht, an dem die kopierten Elemente eingefügt werden sollen |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Kopiert eine angegebene Anzahl von Elementen vom Quell-Array im Stack, beginnend am angegebenen Index, an die angegebene Position im Ziel-Array.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quell-Array im Stack |
| DstType | Typ der Elemente im Ziel-Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Quell-Array im Stack |
| srcIndex | **int64_t** | [Index](../../index/) im Quell-Array im Stack, das den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Ziel-Array |
| dstIndex | **int64_t** | [Index](../../index/) im Ziel-Array, an dem die kopierten Elemente eingefügt werden sollen |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method

Kopiert eine angegebene Anzahl von Elementen vom Quell-Array, beginnend am angegebenen Index, an die angegebene Position im Ziel-Array im Stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quell-Array |
| DstType | Typ der Elemente im Ziel-Array im Stack |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Quell-Array |
| srcIndex | **int64_t** | [Index](../../index/) im Quell-Array, das den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Ziel-Array im Stack |
| dstIndex | **int64_t** | [Index](../../index/) im Ziel-Array im Stack, an dem die kopierten Elemente eingefügt werden sollen |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

Kopiert eine angegebene Anzahl von Elementen vom Quell-Array im Stack, beginnend am angegebenen Index, an die angegebene Position im Ziel-Array im Stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quell-Array im Stack |
| DstType | Typ der Elemente im Ziel-Array im Stack |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Quell-Array im Stack |
| srcIndex | **int64_t** | [Index](../../index/) im Quell-Array im Stack, das den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Ziel-Array im Stack |
| dstIndex | **int64_t** | [Index](../../index/) im Ziel-Array im Stack, an dem die kopierten Elemente eingefügt werden sollen |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

Kopiert eine angegebene Anzahl von Elementen von der Quell-Array-Ansicht, beginnend am angegebenen Index, an die angegebene Position im Ziel-Array im Stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| SrcType | Typ der Elemente im Quell-Array im Stack |
| DstType | Typ der Elemente im Ziel-Array im Stack |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Quell-Array-Ansicht |
| srcIndex | **int64_t** | [Index](../../index/) in der Quell-Array-Ansicht, das den Beginn des zu kopierenden Elementsbereichs bezeichnet |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Ziel-Array im Stack |
| dstIndex | **int64_t** | [Index](../../index/) im Ziel-Array im Stack, an dem die kopierten Elemente eingefügt werden sollen |
| count | **int64_t** | Die Anzahl zu kopierender Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)