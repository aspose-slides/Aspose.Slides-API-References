---
title: CopyTo()
second_title: Aspose.Slides for C++ API referencia
description: Az aktuális tömb összes elemét a megadott cél tömbbe másolja. Az elemek a cél tömbben az arrayIndex argumentummal megadott indexnél kerülnek beillesztésre.
type: docs
weight: 118
url: /hu/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) metódus


Az aktuális tömb összes elemét a megadott cél tömbbe másolja. Az elemek a cél tömbben az arrayIndex argumentummal megadott indexnél kerülnek beillesztésre.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Destination array |
| arrayIndex | int | [Index](../../index/) a cél tömbben, ahol a másolt elemek beillesztését elkezdi |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const metódus


Az aktuális tömb összes elemét a megadott cél tömbbe másolja. Az elemek a cél tömbben a dstIndex argumentummal megadott indexnél kerülnek beillesztésre.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| DstType | A cél tömbben lévő elemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömbben, ahol a másolt elemek beillesztését elkezdi |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const metódus


Az aktuális tömb összes elemét a megadott cél tömb nézetbe másolja. Az elemek a cél tömb nézetben a dstIndex argumentummal megadott indexnél kerülnek beillesztésre.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| DstType | A cél tömb nézetben lévő elemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destination array view |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömb nézetben, ahol a másolt elemek beillesztését elkezdi |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const metódus


Megadott számú elemet másol az aktuális tömbből a megadott pozíciótól kezdve a megadott cél tömbbe. Az elemek a cél tömbben a dstIndex argumentummal megadott indexnél kerülnek beillesztésre.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| DstType | A cél tömbben lévő elemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömbben, ahol a másolást elkezdi |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömbben, ahol a másolt elemek beillesztését elkezdi |
| count | **int64_t** | A másolandó elemek száma |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const metódus


Megadott számú elemet másol az aktuális tömbből a megadott pozíciótól kezdve a megadott cél tömb nézetbe. Az elemek a cél tömb nézetben a dstIndex argumentummal megadott indexnél kerülnek beillesztésre.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| DstType | A cél tömb nézetben lévő elemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destination array view |
| srcIndex | **int64_t** | [Index](../../index/) a forrás tömbben, ahol a másolást elkezdi |
| dstIndex | **int64_t** | [Index](../../index/) a cél tömb nézetben, ahol a másolt elemek beillesztését elkezdi |
| count | **int64_t** | A másolandó elemek száma |

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [Array](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)