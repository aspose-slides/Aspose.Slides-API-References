---
title: IndexOf()
second_title: Aspose.Slides for C++ API Referansı
description: Bir ReadOnlySpan<T> değerinin başka bir ReadOnlySpan<T> içindeki indeksini bulur
type: docs
weight: 144
url: /tr/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyonu


Bir ReadOnlySpan<T> değerinin başka bir ReadOnlySpan<T> içinde indeksini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıklardaki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak span |

### Dönüş Değeri

İlk oluşumun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) fonksiyonu


Bir ReadOnlySpan<T> içinde tek bir değerin indeksini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içinde öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| value | const T\& | Aranacak değer |

### Dönüş Değeri

İlk oluşumun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyonu


Span<T> içinde bir ReadOnlySpan<T> değerinin indeksini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıklardaki öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak span |

### Dönüş Değeri

İlk oluşumun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) fonksiyonu


Bir Span<T> içinde tek bir değerin indeksini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içinde öğelerin tipi |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| value | const T\& | Aranacak değer |

### Dönüş Değeri

İlk oluşumun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonksiyonu


StringComparison kullanarak bir ReadOnlySpan<char16_t> içinde bir ReadOnlySpan<char16_t> değerinin indeksini bulur.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Arama yapılacak span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Aranacak değer |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Kullanılacak dize karşılaştırma türü |

### Dönüş Değeri

İlk oluşumun sıfır tabanlı indeksi, bulunamazsa -1

## Ayrıca bakınız

* Enum [StringComparison](../../system/stringcomparison/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)