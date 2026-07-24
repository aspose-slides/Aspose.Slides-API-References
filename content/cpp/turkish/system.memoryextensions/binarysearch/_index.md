---
title: BinarySearch()
second_title: Aspose.Slides for C++ API Referansı
description: Sıralı bir aralık üzerinde ikili arama gerçekleştirir.
type: docs
weight: 14
url: /tr/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) fonksiyon

Sıralı bir aralık üzerinde ikili arama gerçekleştirir.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### Dönüş Değeri

[Index](../../system/index/) bulunan öğenin, bulunamazsa ekleme noktasının ikili tamamlayıcısı

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) fonksiyon


Özel bir karşılaştırıcı kullanarak sıralı bir aralık üzerinde ikili arama gerçekleştirir.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### Dönüş Değeri

[Index](../../system/index/) bulunan öğenin, bulunamazsa ekleme noktasının ikili tamamlayıcısı

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) fonksiyon


Değiştirilebilir sıralı bir aralık üzerinde ikili arama gerçekleştirir.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### Dönüş Değeri

[Index](../../system/index/) bulunan öğenin, bulunamazsa ekleme noktasının ikili tamamlayıcısı

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) fonksiyon


Özel bir karşılaştırıcı kullanarak değiştirilebilir sıralı bir aralık üzerinde ikili arama gerçekleştirir.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### Dönüş Değeri

[Index](../../system/index/) bulunan öğenin, bulunamazsa ekleme noktasının ikili tamamlayıcısı

## Ayrıca Bakınız

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)