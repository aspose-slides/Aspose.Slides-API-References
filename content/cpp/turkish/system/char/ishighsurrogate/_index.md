---
title: IsHighSurrogate()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizede belirtilen konumdaki karakterin UTF-16 yüksek surrogaat kod birimi olup olmadığını belirler.
type: docs
weight: 40
url: /tr/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String&, int) metot

Belirtilen dizede belirtilen konumdaki karakterin UTF-16 yüksek surrogaat kod birimi olup olmadığını belirler.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Bir dize |
| index | int | Test edilecek karakterin belirtilen dizedeki konumu |

### Dönüş Değeri

Belirtilen konumdaki karakter bir UTF-16 yüksek surrogaat kod birimi ise doğru, aksi takdirde - yanlış

## Char::IsHighSurrogate(const char_t *, int) metot

Belirtilen karakter tamponunda belirtilen konumdaki karakterin yüksek surrogaat olup olmadığını belirler.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char_t * | Karakter tamponunun başlangıcına işaretçi |
| idx | int | Test edilecek karakterin belirtilen tampondaki sıfır tabanlı konumu |

### Dönüş Değeri

Belirtilen konumdaki karakter bir yüksek surrogaat ise doğru, aksi takdirde - yanlış

## Char::IsHighSurrogate(char_t) metot

Belirtilen karakterin yüksek surrogaat olup olmadığını belirler.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Test edilecek karakter |

### Dönüş Değeri

Belirtilen karakter bir yüksek surrogaat ise doğru, aksi takdirde - yanlış

## İlgili

* Sınıf [String](../../string/)
* Sınıf [Char](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)