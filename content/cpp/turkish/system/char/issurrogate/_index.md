---
title: IsSurrogate()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen karakterin bir UTF-16 yedek kod birimi olup olmadığını belirler.
type: docs
weight: 14
url: /tr/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) method


Belirtilen karakterin bir UTF-16 yedek kod birimi olup olmadığını belirler.

```cpp
static bool System::Char::IsSurrogate(char_t c)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Bir karakter |

### Dönüş Değeri

true if the specified character is a UTF-16 surrogate code unit, otherwise - false

## Char::IsSurrogate(const String\&, int) method


Belirtilen dizede, belirtilen indeksteki karakterin bir UTF-16 yedek kod birimi olup olmadığını belirler.

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Bir dize |
| index | int | Belirtilen dizedeki karakterin indeksi |

### Dönüş Değeri

true if the character at the specified index is a UTF-16 surrogate code unit, otherwise - false

## İlgili Bağlantılar

* Sınıf [Char](../)
* Sınıf [String](../../string/)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)