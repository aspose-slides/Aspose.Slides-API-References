---
title: ToUInt16()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizideki belirtilen indeksden başlayarak iki baytı işaretsiz 16-bit tamsayı değerine dönüştürür.
type: docs
weight: 92
url: /tr/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) method


Belirtilen dizideki belirtilen konumdan başlayan iki baytı işaretsiz 16-bit tamsayı değerine dönüştürür.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) dönüştürülecek baytları içeren |
| startIndex | int | [Index](../../index/) dizide, dönüştürme için baytların alınmaya başlanacağı konum |

### Dönüş Değeri

Dönüştürmeden elde edilen işaretsiz 16-bit tam sayı değeri

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method


Belirtilen dizideki belirtilen konumdan başlayan iki baytı işaretsiz 16-bit tamsayı değerine dönüştürür.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | Dönüştürülecek baytları içeren ArrayView |
| startIndex | int | [Index](../../index/) dizide, dönüştürme için baytların alınmaya başlanacağı konum |

### Dönüş Değeri

Dönüştürmeden elde edilen işaretsiz 16-bit tam sayı değeri

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [BitConverter](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)