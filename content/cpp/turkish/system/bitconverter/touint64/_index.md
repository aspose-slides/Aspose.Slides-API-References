---
title: ToUInt64()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen diziden, belirtilen indeksten başlayarak sekiz baytı işaretsiz 64-bit tamsayı değerine dönüştürür.
type: docs
weight: 118
url: /tr/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) metot

Belirtilen dizideki belirli bir indexten başlayarak sekiz baytı işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) dönüştürülecek baytları içeren |
| startIndex | int | [Index](../../index/) dizide baytları almaya başlanacak konum |

### Dönüş Değeri

Dönüşüm sonucunda elde edilen işaretsiz 64-bit tamsayı değeri

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metot

Belirtilen dizideki belirli bir indexten başlayarak sekiz baytı işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | baytları içeren ArrayView |
| startIndex | int | [Index](../../index/) dizide baytları almaya başlanacak konum |

### Dönüş Değeri

Dönüşüm sonucunda elde edilen işaretsiz 64-bit tamsayı değeri

## Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [BitConverter](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)