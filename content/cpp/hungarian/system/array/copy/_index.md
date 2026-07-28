---
title: Copy()
second_title: Aspose.Slides C++ API hivatkozás
description: Átmásolja a megadott számú elemet a forrás tömbből a cél tömbbe.
type: docs
weight: 729
url: /hu/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbből a cél tömbbe.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Forrás tömb |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cél tömb |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbnézetből a cél tömbbe.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Forrás tömbnézet |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cél tömb |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbből a cél tömbnézetbe.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Forrás tömb |
| dstArray | System::Details::ArrayView\<DstType\> | Cél tömbnézet |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbnézetből a cél tömbnézetbe.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Forrás tömbnézet |
| dstArray | System::Details::ArrayView\<DstType\> | Cél tömbnézet |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) method

Átmásolja a megadott számú elemet a stacken lévő forrás tömbből a cél tömbbe.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Forrás tömb a stacken |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cél tömb |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbből a stacken lévő cél tömbbe.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Forrás tömb |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Cél tömb a stacken |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) method

Átmásolja a megadott számú elemet a stacken lévő forrás tömbből a stacken lévő cél tömbbe.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Forrás tömb a stacken |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Cél tömb a stacken |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbből, a megadott indexnél kezdődően, a cél tömb megadott pozíciójába.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | Az elemek típusa a forrás tömbben |
| DstType | Az elemek típusa a cél tömbben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Forrás tömb |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömbben, amely a másolandó elemtartomány elejét jelöli |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cél tömb |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömbben, ahol a másolt elemek beszúrása kezdődik |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbnézetből, a megadott indexnél kezdődően, a cél tömb megadott pozíciójába.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | Az elemek típusa a forrás tömbnézetben |
| DstType | Az elemek típusa a cél tömbben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Forrás tömbnézet |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömbnézetben, amely a másolandó elemtartomány elejét jelöli |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cél tömb |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömbben, ahol a másolt elemek beszúrása kezdődik |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbből, a megadott indexnél kezdődően, a cél tömbnézet megadott pozíciójába.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | Az elemek típusa a forrás tömbben |
| DstType | Az elemek típusa a cél tömbnézetben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Forrás tömb |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömbben, amely a másolandó elemtartomány elejét jelöli |
| dstArray | System::Details::ArrayView\<DstType\> | Cél tömbnézet |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömbnézetben, ahol a másolt elemek beszúrása kezdődik |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbnézetből, a megadott indexnél kezdődően, a cél tömbnézet megadott pozíciójába.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | Az elemek típusa a forrás tömbnézetben |
| DstType | Az elemek típusa a cél tömbnézetben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Forrás tömbnézet |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömbnézetben, amely a másolandó elemtartomány elejét jelöli |
| dstArray | System::Details::ArrayView\<DstType\> | Cél tömbnézet |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömbnézetben, ahol a másolt elemek beszúrása kezdődik |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

Átmásolja a megadott számú elemet a stacken lévő forrás tömbből, a megadott indexnél kezdődően, a cél tömb megadott pozíciójába.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | Az elemek típusa a stacken lévő forrás tömbben |
| DstType | Az elemek típusa a cél tömbben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Forrás tömb a stacken |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömb a stacken, amely a másolandó elemtartomány elejét jelöli |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cél tömb |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömbben, ahol a másolt elemek beszúrása kezdődik |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbből, a megadott indexnél kezdődően, a stacken lévő cél tömb megadott pozíciójába.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | Az elemek típusa a forrás tömbben |
| DstType | Az elemek típusa a stacken lévő cél tömbben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Forrás tömb |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömbben, amely a másolandó elemtartomány elejét jelöli |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Cél tömb a stacken |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömb a stacken, ahol a másolt elemek beszúrása kezdődik |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

Átmásolja a megadott számú elemet a stacken lévő forrás tömbből, a megadott indexnél kezdődően, a stacken lévő cél tömb megadott pozíciójába.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | Az elemek típusa a stacken lévő forrás tömbben |
| DstType | Az elemek típusa a stacken lévő cél tömbben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Forrás tömb a stacken |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömb a stacken, amely a másolandó elemtartomány elejét jelöli |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Cél tömb a stacken |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömb a stacken, ahol a másolt elemek beszúrása kezdődik |
| count | **int64_t** | A másolandó elemek száma |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) method

Átmásolja a megadott számú elemet a forrás tömbnézetből, a megadott indexnél kezdődően, a stacken lévő cél tömb megadott pozíciójába.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| SrcType | Az elemek típusa a forrás tömb nézetben |
| DstType | Az elemek típusa a stacken lévő cél tömbben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Forrás tömbnézet |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömb nézetben, amely a másolandó elemtartomány elejét jelöli |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Cél tömb a stacken |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömb a stacken, ahol a másolt elemek beszúrása kezdődik |
| count | **int64_t** | A másolandó elemek száma |

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Osztály [Array](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)