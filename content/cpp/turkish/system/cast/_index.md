---
title: Cast()
second_title: Aspose.Slides for C++ API Referansı
description: SmartPtr nesneleri üzerinde dönüşüm gerçekleştirir.
type: docs
weight: 2510
url: /tr/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) fonksiyon

[SmartPtr](../smartptr/) nesneleri üzerinde dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Kaynak gösterici. |

### Dönüş Değeri

Dönüşüm izin verildiğinde dönüşüm sonucu.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../smartptr/)
* Yapı [IsExceptionWrapper](../isexceptionwrapper/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)