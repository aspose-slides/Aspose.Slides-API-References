---
title: ToUInt32()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizideki belirtilen indeks başlangıcından dört baytı alarak işaretsiz 32-bit tamsayı değerine dönüştürür.
type: docs
weight: 105
url: /tr/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) method

Belirtilen dizideki belirtilen indeks başlangıcından dört baytı alarak işaretsiz 32-bit tamsayı değerine dönüştürür.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) dönüştürülecek baytları içerir |
| startIndex | int | [Index](../../index/) dizide baytları almaya başlanacak indeks |

### Dönüş Değeri

Dönüştürmeden elde edilen işaretsiz 32-bit tamsayı değeri

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method

Belirtilen dizideki belirtilen indeks başlangıcından dört baytı alarak işaretsiz 32-bit tamsayı değerine dönüştürür.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView baytları içeren |
| startIndex | int | [Index](../../index/) dizide baytları almaya başlanacak indeks |

### Dönüş Değeri

Dönüştürmeden elde edilen işaretsiz 32-bit tamsayı değeri

## İlgili Bağlantılar

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [BitConverter](../)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)