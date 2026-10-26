---
title: CopyTo()
second_title: Aspose.Slides för C++ API-referens
description: Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid index som anges av argumentet arrayIndex.
type: docs
weight: 118
url: /sv/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) metod


Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid index som anges av argumentet arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Destinationsarray |
| arrayIndex | int | [Index](../../index/) i destinationsarray för att börja infoga kopierade element vid |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const metod


Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid index som anges av argumentet dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| DstType | Typ av element i destinationsarray |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destinationsarray |
| dstIndex | **int64_t** | [Index](../../index/) i destinationsarray för att börja infoga kopierade element vid |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const metod


Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayvyn. Elementen infogas i destinationsarrayvyn med start vid index som anges av argumentet dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| DstType | Typ av element i destinationsarrayvy |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destinationsarrayvy |
| dstIndex | **int64_t** | [Index](../../index/) i destinationsarrayvy för att börja infoga kopierade element vid |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const metod


Kopierar ett specificerat antal element från den aktuella arrayen med start på en specificerad position till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid index som anges av argumentet dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| DstType | Typ av element i destinationsarray |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destinationsarray |
| srcIndex | **int64_t** | [Index](../../index/) i källarrayen för att börja kopiera element vid |
| dstIndex | **int64_t** | [Index](../../index/) i destinationsarray för att börja infoga kopierade element vid |
| count | **int64_t** | Antal element att kopiera |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const metod


Kopierar ett specificerat antal element från den aktuella arrayen med start på en specificerad position till den angivna destinationsarrayvyn. Elementen infogas i destinationsarrayvyn med start vid index som anges av argumentet dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| DstType | Typ av element i destinationsarrayvy |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destinationsarrayvy |
| srcIndex | **int64_t** | [Index](../../index/) i källarrayen för att börja kopiera element vid |
| dstIndex | **int64_t** | [Index](../../index/) i destinationsarrayvy för att börja infoga kopierade element vid |
| count | **int64_t** | Antal element att kopiera |

## Se också

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)