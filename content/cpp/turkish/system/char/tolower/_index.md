---
title: ToLower()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen karakteri küçük harfe dönüştürür.
type: docs
weight: 235
url: /tr/system/char/tolower/
---
## Char::ToLower(char_t) metodu

Belirtilen karakteri küçük harfe dönüştürür.

```cpp
static char_t System::Char::ToLower(char_t c)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Dönüştürülecek karakter |

### Dönüş Değeri

Belirtilen karakter büyük harf ise küçük harfe dönüştürülmüş hali, aksi takdirde aynı karakter

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) metodu

Belirtilen karakteri küçük harfe dönüştürür.

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Dönüştürülecek karakter |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kültüre özgü büyük/küçük harf kurallarını sağlayan nesne. |

### Dönüş Değeri

Belirtilen karakter büyük harf ise küçük harfe dönüştürülmüş hali, aksi takdirde aynı karakter

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../sharedptr/)
* Sınıf [Char](../)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)