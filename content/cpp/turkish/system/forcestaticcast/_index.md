---
title: ForceStaticCast()
second_title: Aspose.Slides for C++ API Referansı
description: SmartPtr nesneleri üzerinde gerçek statik dönüşüm gerçekleştirir.
type: docs
weight: 2588
url: /tr/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) fonksiyonu

Gerçek statik dönüşüm [SmartPtr](../smartptr/) nesneleri üzerinde gerçekleştirilir.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaretçi tipi. |
| TFrom | Kaynak işaretçi tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Kaynak gösterici. |

### Dönüş Değeri

Dönüşüm izinliyse dönüşüm sonucu döner, aksi takdirde davranış tanımsızdır.

## İlgili

* Sınıf [SmartPtr](../smartptr/)
* Yapı [CastResult](../castresult/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)