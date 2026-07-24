---
title: Cast_noexcept()
second_title: Aspose.Slides için C++ API Referansı
description: SmartPtr nesneleri üzerinde dönüşüm gerçekleştirir.
type: docs
weight: 2497
url: /tr/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) fonksiyon


[SmartPtr](../smartptr/) nesneleri üzerinde dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaretçi tipi. |
| TFrom | Kaynak işaretçi tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Kaynak işaretçi. |

### Dönüş Değeri

Dönüşüm izin verildiyse dönüşüm sonucu, aksi takdirde nullptr.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../smartptr/)
* Yapı [IsExceptionWrapper](../isexceptionwrapper/)
* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)