---
title: Replace()
second_title: Aspose.Slides for C++ API Referansı
description: Bir Span'da bir değerin tüm tekrarlarını yeni bir değerle değiştirir.
type: docs
weight: 287
url: /tr/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) fonksiyonu

Bir [Span](../../system/span/) içinde bir değerin tüm tekrarlarını yeni bir değerle değiştirir.

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Yerinde değiştirilecek span |
| oldValue | const T\& | Aranacak ve değiştirilecek değer |
| newValue | const T\& | oldValue yerine konulacak yeni değer |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) fonksiyonu

Kaynak'tan hedefe öğeleri kopyalar, kopyalama sırasında belirtilen değerleri değiştirir.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kopyalanacak kaynak [ReadOnlySpan](../../system/readonlyspan/) |
| destination | [Span](../../system/span/)\<T\>\& | Kopyalanacak hedef [Span](../../system/span/) |
| oldValue | const T\& | Kopyalama sırasında aranacak ve değiştirilecek değer |
| newValue | const T\& | oldValue yerine konulacak yeni değer |

## Ayrıca Bakınız

* Sınıf [Span](../../system/span/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Adalanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)