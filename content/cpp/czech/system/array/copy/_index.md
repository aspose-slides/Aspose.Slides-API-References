---
title: Copy()
second_title: Aspose.Slides pro C++ API Reference
description: Zkopíruje zadaný počet prvků ze zdrojového pole do cílového pole.
type: docs
weight: 729
url: /cs/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) metoda

Zkopíruje zadaný počet prvků ze zdrojového pole do cílového pole.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Zdrojové pole |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cílové pole |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) metoda

Zkopíruje zadaný počet prvků ze zobrazení zdrojového pole do cílového pole.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Zobrazení zdrojového pole |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cílové pole |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) metoda

Zkopíruje zadaný počet prvků ze zdrojového pole do zobrazení cílového pole.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Zdrojové pole |
| dstArray | System::Details::ArrayView\<DstType\> | Zobrazení cílového pole |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) metoda

Zkopíruje zadaný počet prvků ze zobrazení zdrojového pole do zobrazení cílového pole.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Zobrazení zdrojového pole |
| dstArray | System::Details::ArrayView\<DstType\> | Zobrazení cílového pole |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) metoda

Zkopíruje zadaný počet prvků ze zásobníkového zdrojového pole do cílového pole.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Zdrojové pole na zásobníku |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cílové pole |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) metoda

Zkopíruje zadaný počet prvků ze zdrojového pole do zásobníkového cílového pole.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Zdrojové pole |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Cílové pole na zásobníku |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) metoda

Zkopíruje zadaný počet prvků ze zásobníkového zdrojového pole do zásobníkového cílového pole.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Zdrojové pole na zásobníku |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Cílové pole na zásobníku |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metoda

Zkopíruje zadaný počet prvků ze zdrojového pole začínajícího na zadaném indexu do určené pozice v cílovém poli.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| SrcType | Typ prvků ve zdrojovém poli |
| DstType | Typ prvků v cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Zdrojové pole |
| srcIndex | **int64_t** | [Index](../../index/) ve zdrojovém poli označující začátek rozsahu položek k zkopírování |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cílové pole |
| dstIndex | **int64_t** | [Index](../../index/) v cílovém poli, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metoda

Zkopíruje zadaný počet prvků ze zobrazení zdrojového pole začínajícího na zadaném indexu do určené pozice v cílovém poli.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| SrcType | Typ prvků ve zobrazení zdrojového pole |
| DstType | Typ prvků v cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Zobrazení zdrojového pole |
| srcIndex | **int64_t** | [Index](../../index/) ve zobrazení zdrojového pole označující začátek rozsahu položek k zkopírování |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cílové pole |
| dstIndex | **int64_t** | [Index](../../index/) v cílovém poli, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metoda

Zkopíruje zadaný počet prvků ze zdrojového pole začínajícího na zadaném indexu do určené pozice v zobrazení cílového pole.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| SrcType | Typ prvků ve zdrojovém poli |
| DstType | Typ prvků ve zobrazení cílového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Zdrojové pole |
| srcIndex | **int64_t** | [Index](../../index/) ve zdrojovém poli označující začátek rozsahu položek k zkopírování |
| dstArray | System::Details::ArrayView\<DstType\> | Zobrazení cílového pole |
| dstIndex | **int64_t** | [Index](../../index/) ve zobrazení cílového pole, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metoda

Zkopíruje zadaný počet prvků ze zobrazení zdrojového pole začínajícího na zadaném indexu do určené pozice v zobrazení cílového pole.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| SrcType | Typ prvků ve zobrazení zdrojového pole |
| DstType | Typ prvků ve zobrazení cílového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Zobrazení zdrojového pole |
| srcIndex | **int64_t** | [Index](../../index/) ve zobrazení zdrojového pole označující začátek rozsahu položek k zkopírování |
| dstArray | System::Details::ArrayView\<DstType\> | Zobrazení cílového pole |
| dstIndex | **int64_t** | [Index](../../index/) ve zobrazení cílového pole, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metoda

Zkopíruje zadaný počet prvků ze zásobníkového zdrojového pole začínajícího na zadaném indexu do určené pozice v cílovém poli.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| SrcType | Typ prvků ve zásobníkovém zdrojovém poli |
| DstType | Typ prvků v cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Zdrojové pole na zásobníku |
| srcIndex | **int64_t** | [Index](../../index/) v zásobníkovém zdrojovém poli označující začátek rozsahu položek k zkopírování |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cílové pole |
| dstIndex | **int64_t** | [Index](../../index/) v cílovém poli, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) metoda

Zkopíruje zadaný počet prvků ze zdrojového pole začínajícího na zadaném indexu do určené pozice v zásobníkovém cílovém poli.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| SrcType | Typ prvků ve zdrojovém poli |
| DstType | Typ prvků v zásobníkovém cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Zdrojové pole |
| srcIndex | **int64_t** | [Index](../../index/) ve zdrojovém poli označující začátek rozsahu položek k zkopírování |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Cílové pole na zásobníku |
| dstIndex | **int64_t** | [Index](../../index/) v zásobníkovém cílovém poli, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metoda

Zkopíruje zadaný počet prvků ze zásobníkového zdrojového pole začínajícího na zadaném indexu do určené pozice v zásobníkovém cílovém poli.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| SrcType | Typ prvků ve zásobníkovém zdrojovém poli |
| DstType | Typ prvků v zásobníkovém cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Zdrojové pole na zásobníku |
| srcIndex | **int64_t** | [Index](../../index/) v zásobníkovém zdrojovém poli označující začátek rozsahu položek k zkopírování |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Cílové pole na zásobníku |
| dstIndex | **int64_t** | [Index](../../index/) v zásobníkovém cílovém poli, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metoda

Zkopíruje zadaný počet prvků ze zobrazení zdrojového pole začínajícího na zadaném indexu do určené pozice v zásobníkovém cílovém poli.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| SrcType | Typ prvků ve zdrojovém poli na zásobníku |
| DstType | Typ prvků v zásobníkovém cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Zobrazení zdrojového pole |
| srcIndex | **int64_t** | [Index](../../index/) ve zobrazení zdrojového pole označující začátek rozsahu položek k zkopírování |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Cílové pole na zásobníku |
| dstIndex | **int64_t** | [Index](../../index/) v zásobníkovém cílovém poli, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)