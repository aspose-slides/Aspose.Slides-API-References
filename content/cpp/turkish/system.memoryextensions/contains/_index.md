---
title: Contains()
second_title: Aspose.Slides for C++ API Referansı
description: Bir salt-okunur span'ın belirli bir değeri içerip içermediğini kontrol eder.
type: docs
weight: 40
url: /tr/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) fonksiyon

Bir salt-okunur span’ın belirli bir değeri içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak span |
| value | const T\& | Aranacak değer |

### Dönüş Değeri

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) fonksiyon

Değiştirilebilir bir span’ın belirli bir değeri içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Aranacak değiştirilebilir span |
| value | const T\& | Aranacak değer |

### Dönüş Değeri

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonksiyon

Bir karakter spanının, belirtilen karşılaştırma kurallarıyla başka bir karakter spanını içerip içermediğini kontrol eder.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Aranacak span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Aranacak span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Gerçekleştirilecek dize karşılaştırma türü |

### Dönüş Değeri

true if value is found in span, false otherwise

## Ayrıca Bakınız

* Enum [StringComparison](../../system/stringcomparison/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* İsim Uzayı [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)