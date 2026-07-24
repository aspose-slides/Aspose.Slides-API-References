---
title: CopyTo()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut dizinin tüm elemanlarını belirtilen hedef diziye kopyalar. Öğeler, arrayIndex bağımsız değişkeniyle belirtilen indeks başlangıcından itibaren hedef diziye eklenir.
type: docs
weight: 118
url: /tr/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) metot


Mevcut dizinin tüm öğelerini belirtilen hedef diziye kopyalar. Öğeler, **arrayIndex** bağımsız değişkeniyle belirtilen indeks başlangıcından itibaren hedef diziye eklenir.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Hedef dizi |
| arrayIndex | int | [Index](../../index/) in destination array to start inserting copied items at |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const metot


Mevcut dizinin tüm öğelerini belirtilen hedef diziye kopyalar. Öğeler, **dstIndex** bağımsız değişkeniyle belirtilen indeks başlangıcından itibaren hedef diziye eklenir.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| DstType | Hedef dizi içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| dstIndex | **int64_t** | [Index](../../index/) in destination array to start inserting copied items at |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const metot


Mevcut dizinin tüm öğelerini belirtilen hedef dizi görünümüne kopyalar. Öğeler, **dstIndex** bağımsız değişkeniyle belirtilen indeks başlangıcından itibaren hedef dizi görünümüne eklenir.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| DstType | Hedef dizi görünümündeki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Hedef dizi görünümü |
| dstIndex | **int64_t** | [Index](../../index/) in destination array view to start inserting copied items at |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const metot


Belirtilen konumdan başlayarak mevcut diziden belirtilen sayıda öğeyi belirtilen hedef diziye kopyalar. Öğeler, **dstIndex** bağımsız değişkeniyle belirtilen indeks başlangıcından itibaren hedef diziye eklenir.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| DstType | Hedef dizi içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Hedef dizi |
| srcIndex | **int64_t** | [Index](../../index/) in source array to start copying items at |
| dstIndex | **int64_t** | [Index](../../index/) in destination array to start inserting copied items at |
| count | **int64_t** | Kopyalanacak eleman sayısı |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const metot


Belirtilen konumdan başlayarak mevcut diziden belirtilen sayıda öğeyi belirtilen hedef dizi görünümüne kopyalar. Öğeler, **dstIndex** bağımsız değişkeniyle belirtilen indeks başlangıcından itibaren hedef dizi görünümüne eklenir.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| DstType | Hedef dizi görünümündeki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Hedef dizi görünümü |
| srcIndex | **int64_t** | [Index](../../index/) in source array to start copying items at |
| dstIndex | **int64_t** | [Index](../../index/) in destination array view to start inserting copied items at |
| count | **int64_t** | Kopyalanacak eleman sayısı |

## Ayrıca bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [Array](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)