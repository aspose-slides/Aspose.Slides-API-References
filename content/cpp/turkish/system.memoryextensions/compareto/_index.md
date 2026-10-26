---
title: CompareTo()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dize karşılaştırma kurallarıyla iki karakter aralığını karşılaştırır.
type: docs
weight: 404
url: /tr/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonksiyon

Belirtilen dize karşılaştırma kurallarıyla iki karakter aralığını karşılaştırır.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | İlk karakter aralığı |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | İkinci karakter aralığı |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Gerçekleştirilecek dize karşılaştırma türü |

### Dönüş Değeri

Eğer span < other ise negatif değer, eşit ise sıfır, span > other ise pozitif değer

## Ayrıca Bakınız

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)