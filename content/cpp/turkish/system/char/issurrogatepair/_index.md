---
title: IsSurrogatePair()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen iki karakterin bir UTF-16 surrogate çifti oluşturup oluşturmadığını belirler.
type: docs
weight: 27
url: /tr/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) metot


Belirtilen iki karakterin bir UTF-16 surrogate çifti olup olmadığını belirler.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| highSurrogate | char_t | Yüksek surrogate olup olmadığı test edilen bir karakter |
| lowSurrogate | char_t | Düşük surrogate olup olduğu test edilen bir karakter |

### Dönüş Değeri

True if the specified characters form a surrogate pair, otherwise - false

## Char::IsSurrogatePair(const String\&, int) metot


Belirtilen karakter tamponundaki iki ardışık karakterin bir surrogate çifti olup olmadığını belirler.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../string/)\& | Bir dize |
| index | int | Belirtilen tamponda test edilecek karakter dizisinin başladığı sıfır tabanlı bir indeks |

### Dönüş Değeri

True if the specified characters are a surrogate pair, otherwise - false

## Ayrıca Bakınız

* Sınıf [Char](../)
* Sınıf [String](../../string/)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)