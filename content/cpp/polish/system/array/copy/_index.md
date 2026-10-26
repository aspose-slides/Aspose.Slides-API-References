---
title: Copy()
second_title: Aspose.Slides dla C++ - Referencja API
description: Kopiuje określoną liczbę elementów z tablicy źródłowej do tablicy docelowej.
type: docs
weight: 729
url: /pl/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej do tablicy docelowej.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tablica źródłowa |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) metoda

Kopiuje określoną liczbę elementów z widoku tablicy źródłowej do tablicy docelowej.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Widok tablicy źródłowej |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej do widoku tablicy docelowej.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tablica źródłowa |
| dstArray | System::Details::ArrayView\<DstType\> | Widok tablicy docelowej |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) metoda

Kopiuje określoną liczbę elementów z widoku tablicy źródłowej do widoku tablicy docelowej.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Widok tablicy źródłowej |
| dstArray | System::Details::ArrayView\<DstType\> | Widok tablicy docelowej |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej na stosie do tablicy docelowej.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Tablica źródłowa na stosie |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej do tablicy docelowej na stosie.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tablica źródłowa |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Tablica docelowa na stosie |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej na stosie do tablicy docelowej na stosie.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Tablica źródłowa na stosie |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Tablica docelowa na stosie |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej zaczynającej się od podanego indeksu do określonej pozycji w tablicy docelowej.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w tablicy źródłowej |
| DstType | Typ elementów w tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tablica źródłowa |
| srcIndex | **int64_t** | [Index](../../index/) w tablicy źródłowej określające początek zakresu elementów do skopiowania |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej określające miejsce rozpoczęcia wstawiania skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metoda

Kopiuje określoną liczbę elementów z widoku tablicy źródłowej zaczynającej się od podanego indeksu do określonej pozycji w tablicy docelowej.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w widoku tablicy źródłowej |
| DstType | Typ elementów w tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Widok tablicy źródłowej |
| srcIndex | **int64_t** | [Index](../../index/) w widoku tablicy źródłowej określające początek zakresu elementów do skopiowania |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej określające miejsce rozpoczęcia wstawiania skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej zaczynającej się od podanego indeksu do określonej pozycji w widoku tablicy docelowej.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w tablicy źródłowej |
| DstType | Typ elementów w widoku tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tablica źródłowa |
| srcIndex | **int64_t** | [Index](../../index/) w tablicy źródłowej określające początek zakresu elementów do skopiowania |
| dstArray | System::Details::ArrayView\<DstType\> | Widok tablicy docelowej |
| dstIndex | **int64_t** | [Index](../../index/) w widoku tablicy docelowej określające miejsce rozpoczęcia wstawiania skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metoda

Kopiuje określoną liczbę elementów z widoku tablicy źródłowej zaczynającej się od podanego indeksu do określonej pozycji w widoku tablicy docelowej.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w widoku tablicy źródłowej |
| DstType | Typ elementów w widoku tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Widok tablicy źródłowej |
| srcIndex | **int64_t** | [Index](../../index/) w widoku tablicy źródłowej określające początek zakresu elementów do skopiowania |
| dstArray | System::Details::ArrayView\<DstType\> | Widok tablicy docelowej |
| dstIndex | **int64_t** | [Index](../../index/) w widoku tablicy docelowej określające miejsce rozpoczęcia wstawiania skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej na stosie zaczynającej się od podanego indeksu do określonej pozycji w tablicy docelowej.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w tablicy źródłowej na stosie |
| DstType | Typ elementów w tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Tablica źródłowa na stosie |
| srcIndex | **int64_t** | [Index](../../index/) w tablicy źródłowej na stosie określające początek zakresu elementów do skopiowania |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tablica docelowa |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej określające miejsce rozpoczęcia wstawiania skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej zaczynającej się od podanego indeksu do określonej pozycji w tablicy docelowej na stosie.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w tablicy źródłowej |
| DstType | Typ elementów w tablicy docelowej na stosie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tablica źródłowa |
| srcIndex | **int64_t** | [Index](../../index/) w tablicy źródłowej określające początek zakresu elementów do skopiowania |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Tablica docelowa na stosie |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej na stosie określające miejsce rozpoczęcia wstawiania skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metoda

Kopiuje określoną liczbę elementów z tablicy źródłowej na stosie zaczynającej się od podanego indeksu do określonej pozycji w tablicy docelowej na stosie.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w tablicy źródłowej na stosie |
| DstType | Typ elementów w tablicy docelowej na stosie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Tablica źródłowa na stosie |
| srcIndex | **int64_t** | [Index](../../index/) w tablicy źródłowej na stosie określające początek zakresu elementów do skopiowania |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Tablica docelowa na stosie |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej na stosie określające miejsce rozpoczęcia wstawiania skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metoda

Kopiuje określoną liczbę elementów z widoku tablicy źródłowej zaczynającej się od podanego indeksu do określonej pozycji w tablicy docelowej na stosie.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| SrcType | Typ elementów w widoku tablicy źródłowej |
| DstType | Typ elementów w tablicy docelowej na stosie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Widok tablicy źródłowej |
| srcIndex | **int64_t** | [Index](../../index/) w widoku tablicy źródłowej określające początek zakresu elementów do skopiowania |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Tablica docelowa na stosie |
| dstIndex | **int64_t** | [Index](../../index/) w tablicy docelowej na stosie określające miejsce rozpoczęcia wstawiania skopiowanych elementów |
| count | **int64_t** | Liczba elementów do skopiowania |

## Patrz także

* Definicja typu [ArrayPtr](../../arrayptr/)
* Klasa [Array](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)