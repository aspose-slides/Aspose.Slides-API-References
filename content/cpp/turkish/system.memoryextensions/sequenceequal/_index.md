---
title: SequenceEqual()
second_title: Aspose.Slides for C++ API Referansı
description: İki ReadOnlySpan'in aynı sırada aynı öğelere sahip olup olmadığını belirler.
type: docs
weight: 326
url: /tr/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon


İki ReadOnlySpan'in aynı sırada aynı öğelere sahip olup olmadığını belirler.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak ilk span |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak ikinci span |

### Dönüş Değeri

spans aynı uzunluğa sahipse ve tüm öğeler eşitse true, aksi takdirde false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon


Bir [Span](../../system/span/) ve [ReadOnlySpan](../../system/readonlyspan/)'nin aynı sırada aynı öğelere sahip olup olmadığını belirler.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Karşılaştırılacak [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak [ReadOnlySpan](../../system/readonlyspan/) |

### Dönüş Değeri

spans aynı uzunluğa sahipse ve tüm öğeler eşitse true, aksi takdirde false

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) fonksiyon


İki ReadOnlySpan'in özel bir karşılaştırıcı kullanarak eşit öğelere sahip olup olmadığını belirler.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |
| TComparer | Karşılaştırıcı nesnesinin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak ilk span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak ikinci span |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Öğeleri karşılaştırmak için akıllı gösterici |

### Dönüş Değeri

spans aynı uzunluğa sahipse ve comparer tüm öğeleri eşit kabul ederse true, aksi takdirde false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) fonksiyon


Bir [Span](../../system/span/) ve [ReadOnlySpan](../../system/readonlyspan/)'nin özel bir karşılaştırıcı kullanarak eşit öğelere sahip olup olmadığını belirler.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |
| TComparer | Karşılaştırıcı nesnesinin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Karşılaştırılacak [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak [ReadOnlySpan](../../system/readonlyspan/) |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Öğeleri karşılaştırmak için akıllı gösterici |

### Dönüş Değeri

spans aynı uzunluğa sahipse ve comparer tüm öğeleri eşit kabul ederse true, aksi takdirde false

## Bakınız

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)