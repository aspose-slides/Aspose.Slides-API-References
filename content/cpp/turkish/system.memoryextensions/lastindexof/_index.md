---
title: LastIndexOf()
second_title: Aspose.Slides için C++ API Referansı
description: Bir aralık içinde bir dizinin son gerçekleşmesini bulur.
type: docs
weight: 209
url: /tr/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Bir aralık içinde bir dizinin son gerçekleşmesini bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak aralık |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranan dizi |

### Dönüş Değeri

Son gerçekleşmenin sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) fonksiyon

Bir aralık içinde tek bir değerin son gerçekleşmesini bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak aralık |
| value | const T\& | Aranan değer |

### Dönüş Değeri

Son gerçekleşmenin sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Değiştirilebilir bir aralık içinde bir dizinin son gerçekleşmesini bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak aralık |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranan dizi |

### Dönüş Değeri

Son gerçekleşmenin sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) fonksiyon

Değiştirilebilir bir aralık içinde tek bir değerin son gerçekleşmesini bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak aralık |
| value | const T\& | Aranan değer |

### Dönüş Değeri

Son gerçekleşmenin sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonksiyon

Belirtilen dize karşılaştırması kullanarak bir aralık içinde bir değerin son gerçekleşmesini bulur.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Arama yapılacak aralık |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Aranan değer |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Gerçekleştirilecek dize karşılaştırma türü |

### Dönüş Değeri

Son gerçekleşmenin sıfır tabanlı indeksi, bulunamazsa -1

## Ayrıca Bakınız

* Enum [StringComparison](../../system/stringcomparison/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)