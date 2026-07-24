---
title: MakeYieldEnumerable()
second_title: Aspose.Slides for C++ API Referansı
description: Bir yield işlevinden bir IEnumerable oluşturur.
type: docs
weight: 2419
url: /tr/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) function

Bir yield işlevinden bir IEnumerable oluşturur.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dizideki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Yürütülecek yield işlevi |

### Dönüş Değeri

IEnumerable için paylaşımlı gösterici

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Sınıf [IEnumerable](../../system.collections.generic/ienumerable/)
* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)