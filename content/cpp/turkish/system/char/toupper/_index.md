---
title: ToUpper()
second_title: Aspose.Slides C++ için API Referansı
description: Belirtilen karakteri büyük harfe dönüştürür.
type: docs
weight: 222
url: /tr/system/char/toupper/
---
## Char::ToUpper(char_t) yöntemi

Belirtilen karakteri büyük harfe dönüştürür.

```cpp
static char_t System::Char::ToUpper(char_t c)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Dönüştürülecek karakter |

### Dönüş Değeri

Belirtilen karakter, küçük harf ise büyük harfe dönüştürülmüş hali, aksi takdirde - belirtilen karakter

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi

Belirtilen karakteri büyük harfe dönüştürür.

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Dönüştürülecek karakter |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kültüre özgü büyük/küçük harf kurallarını sağlayan bir nesne. |

### Dönüş Değeri

Belirtilen karakter, küçük harf ise büyük harfe dönüştürülmüş hali, aksi takdirde - belirtilen karakter

## İlgili

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Char](../)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)