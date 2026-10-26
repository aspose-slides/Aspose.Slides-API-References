---
title: ToInt64()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizideki belirtilen indeksten başlayarak sekiz baytı 64 bit tam sayı değerine dönüştürür.
type: docs
weight: 79
url: /tr/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) metod

Belirtilen dizideki belirtilen indeksten başlayarak sekiz baytı 64 bit tam sayı değerine dönüştürür.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) baytları içeren |
| startIndex | int | [Index](../../index/) dizide baytları dönüştürmeye başlanacak konum |

### Dönüş Değeri

Dönüştürmeden elde edilen 64 bit tam sayı değeri

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metod

Belirtilen dizideki belirtilen indeksten başlayarak sekiz baytı 64 bit tam sayı değerine dönüştürür.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | baytları içeren ArrayView |
| startIndex | int | [Index](../../index/) dizide baytları dönüştürmeye başlanacak konum |

### Dönüş Değeri

Dönüştürmeden elde edilen 64 bit tam sayı değeri

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)