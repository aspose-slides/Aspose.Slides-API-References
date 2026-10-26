---
title: SequenceEqualImpl()
second_title: Aspose.Slides for C++ API Referansı
description: İki span'ın belirtilen konumlardan başlayarak eşit olup olmadığını kontrol eder.
type: docs
weight: 27
url: /tr/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) fonksiyon

İki span'ın belirtilen konumlardan başlayarak eşit olup olmadığını kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lardaki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İlk span |
| start | const **int32_t** | İlk span içindeki başlangıç indeksi |
| length | **int32_t** | Karşılaştırılacak öğe sayısı |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İkinci span |

### Dönüş Değeri

Belirtilen aralıklar eşitse true, aksi takdirde false

## Ayrıca

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Ad alanı [System::MemoryExtensions::Details](../)
* Kütüphane [Aspose.Slides](../../)