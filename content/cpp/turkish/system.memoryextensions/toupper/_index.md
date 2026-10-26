---
title: ToUpper()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kültürü kullanarak karakterleri büyük harfe dönüştürür.
type: docs
weight: 469
url: /tr/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) fonksiyon

Belirtilen kültürü kullanarak karakterleri büyük harfe dönüştürür.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Dönüştürülecek kaynak karakter aralığı |
| destination | [Span](../../system/span/)\<char16_t\>\& | Dönüştürülmüş karakterlerin depolanacağı hedef aralık |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Dönüştürme için kullanılacak kültür (geçerli kültür için nullptr) |

### Dönüş Değeri

Dönüştürülen karakter sayısı, ya da hedef çok küçükse -1

## İlgili

* Typedef [SharedPtr](../../system/sharedptr/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Sınıf [CultureInfo](../../system.globalization/cultureinfo/)
* Ad Alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)