---
title: MakeYieldEnumerator()
second_title: Aspose.Slides for C++ API Referansı
description: Bir yield işlevinden IEnumerator oluşturur.
type: docs
weight: 2432
url: /tr/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) fonksiyon


Bir yield işlevinden bir IEnumerator oluşturur.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
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

IEnumerator için ortak işaretçi

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Sınıf [IEnumerator](../../system.collections.generic/ienumerator/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)