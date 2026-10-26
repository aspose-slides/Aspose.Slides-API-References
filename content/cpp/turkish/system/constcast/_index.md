---
title: ConstCast()
second_title: Aspose.Slides for C++ API Referansı
description: Kaldırılmış cast'lerin sonu.
type: docs
weight: 2575
url: /tr/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) fonksiyon

Kaldırılmış cast'lerin sonu.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tür. |
| TFrom | Kaynak işaret edilen tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Kaynak gösterici. |

### Döndürme Değeri

Cast izin verildiyse dönüşüm sonucu, aksi takdirde nullptr.

## Açıklamalar

[SmartPtr](../smartptr/) nesneleri üzerinde const cast gerçekleştirir.

## İlgili

* Sınıf [SmartPtr](../smartptr/)
* Yapı [CastResult](../castresult/)
* İsim Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)