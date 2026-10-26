---
title: CommonPrefixLength()
second_title: Aspose.Slides için C++ API Referansı
description: İki aralık arasındaki ortak ön ekin uzunluğunu bulur.
type: docs
weight: 27
url: /tr/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

İki aralık arasındaki ortak ön ekin uzunluğunu bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıkların elemanlarının türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İlk aralık |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İkinci aralık |

### Dönüş Değeri

Her iki aralığın da başlangıcındaki eşleşen elemanların sayısı

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Değiştirilebilir bir aralık ile salt-okunur bir aralık arasındaki ortak ön ekin uzunluğunu bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıkların elemanlarının türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Değiştirilebilir aralık |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Salt-okunur aralık |

### Dönüş Değeri

Her iki aralığın da başlangıcındaki eşleşen elemanların sayısı

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) function

İki değiştirilebilir aralık arasındaki ortak ön ekin uzunluğunu bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıkların elemanlarının türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | İlk değiştirilebilir aralık |
| other | const [Span](../../system/span/)\<T\>\& | İkinci değiştirilebilir aralık |

### Dönüş Değeri

Her iki aralığın da başlangıcındaki eşleşen elemanların sayısı

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Özel bir eşitlik karşılaştırıcısı kullanarak iki aralık arasındaki ortak ön ekin uzunluğunu bulur.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıkların elemanlarının türü |
| TEqualityComparer | Eşitlik karşılaştırıcısının türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İlk aralık |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İkinci aralık |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Eleman karşılaştırması için kullanılacak eşitlik karşılaştırıcısı |

### Dönüş Değeri

Her iki aralığın da başlangıcındaki eşleşen elemanların sayısı

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Özel bir eşitlik karşılaştırıcısı kullanarak değiştirilebilir bir aralık ile salt-okunur bir aralık arasındaki ortak ön ekin uzunluğunu bulur.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıkların elemanlarının türü |
| TEqualityComparer | Eşitlik karşılaştırıcısının türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Değiştirilebilir aralık |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Salt-okunur aralık |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Eleman karşılaştırması için kullanılacak eşitlik karşılaştırıcısı |

### Dönüş Değeri

Her iki aralığın da başlangıcındaki eşleşen elemanların sayısı

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Özel bir eşitlik karşılaştırıcısı kullanarak iki değiştirilebilir aralık arasındaki ortak ön ekin uzunluğunu bulur.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıkların elemanlarının türü |
| TEqualityComparer | Eşitlik karşılaştırıcısının türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | İlk değiştirilebilir aralık |
| other | const [Span](../../system/span/)\<T\>\& | İkinci değiştirilebilir aralık |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Eleman karşılaştırması için kullanılacak eşitlik karşılaştırıcısı |

### Dönüş Değeri

Her iki aralığın da başlangıcındaki eşleşen elemanların sayısı

## Ayrıca Bakınız

* Typedef [SharedPtr](../../system/sharedptr/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)