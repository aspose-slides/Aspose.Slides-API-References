---
title: CopyTo()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Zkopíruje všechny prvky aktuálního pole do určeného cílového pole. Prvky jsou vloženy do cílového pole začínající indexem určeným argumentem arrayIndex.
type: docs
weight: 118
url: /cs/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) metoda

Zkopíruje všechny prvky aktuálního pole do určeného cílového pole. Prvky jsou vloženy do cílového pole začínající indexem určeným argumentem arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Cílové pole |
| arrayIndex | int | [Index](../../index/) v cílovém poli, kde začít vkládat zkopírované položky |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const metoda

Zkopíruje všechny prvky aktuálního pole do určeného cílového pole. Prvky jsou vloženy do cílového pole začínající indexem určeným argumentem dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| DstType | Typ prvků v cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cílové pole |
| dstIndex | **int64_t** | [Index](../../index/) v cílovém poli, kde začít vkládat zkopírované položky |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const metoda

Zkopíruje všechny prvky aktuálního pole do určeného cílového pohledu na pole. Prvky jsou vloženy do cílového pohledu na pole začínající indexem určeným argumentem dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| DstType | Typ prvků v cílovém pohledu na pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Cílový pohled na pole |
| dstIndex | **int64_t** | [Index](../../index/) v cílovém pohledu na pole, kde začít vkládat zkopírované položky |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const metoda

Zkopíruje určený počet prvků ze současného pole počínaje určenou pozicí do určeného cílového pole. Prvky jsou vloženy do cílového pole začínající indexem určeným argumentem dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| DstType | Typ prvků v cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Cílové pole |
| srcIndex | **int64_t** | [Index](../../index/) ve zdrojovém poli, kde začít kopírovat položky |
| dstIndex | **int64_t** | [Index](../../index/) v cílovém poli, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const metoda

Zkopíruje určený počet prvků ze současného pole počínaje určenou pozicí do určeného cílového pohledu na pole. Prvky jsou vloženy do cílového pohledu na pole začínající indexem určeným argumentem dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| DstType | Typ prvků v cílovém pohledu na pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Cílový pohled na pole |
| srcIndex | **int64_t** | [Index](../../index/) ve zdrojovém poli, kde začít kopírovat položky |
| dstIndex | **int64_t** | [Index](../../index/) v cílovém pohledu na pole, kde začít vkládat zkopírované položky |
| count | **int64_t** | Počet prvků k zkopírování |

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)