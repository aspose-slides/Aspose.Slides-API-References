---
title: ToInt32()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen diziden, belirtilen indeksten başlayarak dört baytı 32-bit tamsayı değerine dönüştürür.
type: docs
weight: 66
url: /tr/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) metot

Belirtilen diziden, belirtilen indeksten başlayarak dört baytı 32-bit tamsayı değerine dönüştürür.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) dönüştürülecek baytları içeren |
| startIndex | int | [Index](../../index/) dizide, baytları dönüştürmeye başlanacak konum |

### Dönüş Değeri

Dönüşüm sonucunda elde edilen 32-bit tamsayı değeri

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metot

Belirtilen diziden, belirtilen indeksten başlayarak dört baytı 32-bit tamsayı değerine dönüştürür.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, dönüştürülecek baytları içeren |
| startIndex | int | [Index](../../index/) dizide, baytları dönüştürmeye başlanacak konum |

### Dönüş Değeri

Dönüşüm sonucunda elde edilen 32-bit tamsayı değeri

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [BitConverter](../)
* Ad Alanı [System](../../)
* Library [Aspose.Slides](../../../)