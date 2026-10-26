---
title: EndsWith()
second_title: Aspose.Slides için C++ API Referansı
description: Bir ReadOnlySpan<T>'nin tek bir değerle bitip bitmediğini belirler.
type: docs
weight: 131
url: /tr/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) fonksiyonu

Bir ReadOnlySpan<T>'nin tek bir değerle bitip bitmediğini belirler.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kontrol edilecek span |
| value | const T\& | Span sonunda kontrol edilecek değer |

### Dönüş Değeri

true if the span ends with the value, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyonu

Bir ReadOnlySpan<T>'nin başka bir ReadOnlySpan<T> ile bitip bitmediğini belirler.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kontrol edilecek span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Hedef span’in sonunda kontrol edilecek span |

### Dönüş Değeri

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyonu

Bir Span<T>'nin ReadOnlySpan<T> ile bitip bitmediğini belirler.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Kontrol edilecek span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Hedef span’in sonunda kontrol edilecek span |

### Dönüş Değeri

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) fonksiyonu

Bir ReadOnlySpan<T>'nin Span<T> ile bitip bitmediğini belirler.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kontrol edilecek span |
| value | const [Span](../../system/span/)\<T\>\& | Hedef span’in sonunda kontrol edilecek span |

### Dönüş Değeri

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) fonksiyonu

Bir Span<T>'nin başka bir Span<T> ile bitip bitmediğini belirler.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Kontrol edilecek span |
| value | const [Span](../../system/span/)\<T\>\& | Hedef span’in sonunda kontrol edilecek span |

### Dönüş Değeri

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonksiyonu

Bir ReadOnlySpan<char16_t>'nin belirtilen değeri, StringComparison kullanarak bitip bitmediğini belirler.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kontrol edilecek span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span sonunda kontrol edilecek değer |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Kullanılacak dize karşılaştırma türü |

### Dönüş Değeri

true if the span ends with the value, false otherwise

## Ayrıca Bakınız

* Enum [StringComparison](../../system/stringcomparison/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)