---
title: StartsWith()
second_title: Aspose.Slides için C++ API Referansı
description: Span'in belirtilen değerle başlayıp başlamadığını kontrol eder.
type: docs
weight: 352
url: /tr/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) fonksiyon

Span'in belirtilen değerle başlayıp başlamadığını kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kontrol edilecek span |
| value | const T\& | Span'in başındaki değeri kontrol etmek için kullanılan değer |

### Dönüş Değeri

span değerle başlıyorsa true, aksi takdirde false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Span'in belirtilen değer span'iyle başlayıp başlamadığını kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kontrol edilecek span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Başlangıçta kontrol edilecek değerleri içeren span |

### Dönüş Değeri

span değer span'iyle başlıyorsa true, aksi takdirde false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Değiştirilebilir span'in belirtilen yalnızca okuma değer span'iyle başlayıp başlamadığını kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Kontrol edilecek değiştirilebilir span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Başlangıçta kontrol edilecek değerleri içeren yalnızca okuma span |

### Dönüş Değeri

span değer span'iyle başlıyorsa true, aksi takdirde false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) fonksiyon

Yalnızca okuma span'in belirtilen değiştirilebilir değer span'iyle başlayıp başlamadığını kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kontrol edilecek yalnızca okuma span |
| value | const [Span](../../system/span/)\<T\>\& | Başlangıçta kontrol edilecek değerleri içeren değiştirilebilir span |

### Dönüş Değeri

span değer span'iyle başlıyorsa true, aksi takdirde false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonksiyon

Karakter span'inin, dizge karşılaştırması kullanarak belirtilen değer span'iyle başlayıp başlamadığını kontrol eder.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kontrol edilecek karakter span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Başlangıçta kontrol edilecek değerleri içeren karakter span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Yapılacak dizge karşılaştırma türü |

### Dönüş Değeri

span değer span'iyle başlıyorsa true, aksi takdirde false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) fonksiyon

Dize span'inin belirtilen karakter dizisiyle başlayıp başlamadığını kontrol eder.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | Kontrol edilecek dize span |
| val | const char16_t * | Başlangıçta kontrol edilecek karakter dizisi |

### Dönüş Değeri

span değer span'iyle başlıyorsa true, aksi takdirde false

## Ayrıca Bakınız

* Enum [StringComparison](../../system/stringcomparison/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Sınıf [String](../../system/string/)
* AdAlanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)