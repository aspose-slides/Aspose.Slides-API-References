---
title: SequenceCompareTo()
second_title: Aspose.Slides for C++ API Referansı
description: İki ReadOnlySpans'i sözlük sırasına göre karşılaştırır.
type: docs
weight: 313
url: /tr/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

İki ReadOnlySpan'i sözlük sırasına göre karşılaştırır.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki elemanların tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak ilk span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak ikinci span |

### Dönüş Değeri

- 1 eğer span < other, 0 eğer span == other, 1 eğer span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Bir [Span](../../system/span/) ve [ReadOnlySpan](../../system/readonlyspan/)'i sözlük sırasına göre karşılaştırır.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki elemanların tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Karşılaştırılacak [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak [ReadOnlySpan](../../system/readonlyspan/) |

### Dönüş Değeri

- 1 eğer span < other, 0 eğer span == other, 1 eğer span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) fonksiyon

Bir [ReadOnlySpan](../../system/readonlyspan/) ve [Span](../../system/span/)'i sözlük sırasına göre karşılaştırır.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki elemanların tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Karşılaştırılacak [ReadOnlySpan](../../system/readonlyspan/) |
| other | const [Span](../../system/span/)\<T\>\& | Karşılaştırılacak [Span](../../system/span/) |

### Dönüş Değeri

- 1 eğer span < other, 0 eğer span == other, 1 eğer span > other

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)