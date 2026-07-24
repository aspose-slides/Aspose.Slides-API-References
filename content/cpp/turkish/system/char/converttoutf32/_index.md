---
title: ConvertToUtf32()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen UTF-16 eşleni çiftini UTF-32 kod birimine dönüştürür.
type: docs
weight: 287
url: /tr/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) metod


Belirtilen UTF-16 eşleni çiftini UTF-32 kod birimine dönüştürür.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| highSurrogate | char_t | Dönüştürülecek UTF-16 eşleni çiftinin yüksek eşleni |
| lowSurrogate | char_t | Dönüştürülecek UTF-16 eşleni çiftinin düşük eşleni |

### Dönüş Değeri

Dönüşüm sonucunda elde edilen bir UTF-32 kod birimi

## Char::ConvertToUtf32(const String\&, int) metod


Bir dizede belirtilen konumda bulunan UTF-16 kodlu bir karakterin veya eşleni çiftinin değerini UTF-32 kod birimine dönüştürür.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Bir karakter veya eşleni çift içeren bir dize |
| index | int | Belirtilen dizede karakterin veya eşleni çiftinin indeks konumu |

### Dönüş Değeri

Dönüşüm sonucunda elde edilen bir UTF-32 kod birimi

## Ayrıca Bakınız

* Sınıf [Char](../)
* Sınıf [String](../../string/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)