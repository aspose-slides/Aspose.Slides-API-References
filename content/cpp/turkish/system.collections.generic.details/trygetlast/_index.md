---
title: TryGetLast()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun son elemanını almaya çalışır.
type: docs
weight: 261
url: /tr/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) fonksiyon


Koleksiyonun son elemanını almaya çalışır.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Koleksiyon elemanlarının tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Elemanın alınacağı koleksiyon. |
| found | **bool**\& | Çıktı parametresi. Koleksiyon bir eleman içerdiğinde true döner. Aksi takdirde false döner. |

### Dönüş Değeri

Koleksiyonun son elemanını döndürür. Koleksiyon boş olduğunda tipin varsayılan değeri döndürülür.

## Ayrıca

* Sınıf [IEnumerable](../../system.collections.generic/ienumerable/)
* Ad Alanı [System::Collections::Generic::Details](../)
* Kütüphane [Aspose.Slides](../../)