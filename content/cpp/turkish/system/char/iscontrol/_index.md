---
title: IsControl()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen karakter tamponundaki belirtilen indeksteki karakterin Unicode kontrol karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler.
type: docs
weight: 66
url: /tr/system/char/iscontrol/
---
## Char::IsControl(const char_t *, int) metodu

Belirtilen karakter tamponundaki belirtilen indeksteki karakterin Unicode kontrol karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler.

```cpp
static bool System::Char::IsControl(const char_t *str, int idx)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char_t * | Karakter tamponunun başlangıcına işaretçi |
| idx | int | Test edilecek karakterin belirtilen tampondaki sıfır tabanlı indeksi |

### Dönüş Değeri

True if the character at the specified index is a Unicode control character, otherwise - false

## Char::IsControl(char_t) metodu

Belirtilen karakterin Unicode kontrol karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler.

```cpp
static bool System::Char::IsControl(char_t c)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Test edilecek karakter |

### Dönüş Değeri

True if the specified character is a Unicode control character, otherwise - false

## Bakınız

* Sınıf [Char](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)