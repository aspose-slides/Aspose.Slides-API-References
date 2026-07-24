---
title: DynamicCastArray()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizinin öğelerinin farklı bir tipe dönüştürülmesini gerçekleştirir.
type: docs
weight: 2991
url: /tr/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) fonksiyon


Belirtilen dizinin öğelerinin farklı bir tipe dönüştürülmesini gerçekleştirir.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| To | Belirtilen dizinin öğelerinin dönüştürüleceği tip |
| From | Dönüştürülmesi gereken öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Öğeleri dönüştürmek için diziyi içeren paylaşımlı işaretçi |

### Dönüş Değeri

**from** öğelerine eşdeğer **To** tipindeki öğeler içeren yeni bir diziye işaretçi

Kullanımdan Kaldırılmış
:   Geriye dönük uyumluluk için eklendi. Bunun yerine ExplicitCast kullanın.

## Diğer Bilgiler

* Typedef [SharedPtr](../sharedptr/)
* Sınıf [Array](../array/)
* İsim Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)