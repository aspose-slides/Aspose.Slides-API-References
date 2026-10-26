---
title: GetValueOf()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen adla enum constant'ın kutulanmış değerini döndürür.
type: docs
weight: 53
url: /tr/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const metodu


Belirtilen adla enum constant'ın kutulanmış değerini döndürür.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../string/)\& | Enum constant'ın adı |
| ignoreCase | **bool** | İsim büyük/küçük harfe duyarlılığın enum constant adını yorumlarken göz ardı edilip edilmeyeceğini belirtir |

### Dönüş Değeri

**str** içinde belirtilen adın enum constant'ının kutulanmış değeri.

## EnumValues::GetValueOf(long) const metodu


Belirtilen değerle enum constant'ın kutulanmış değerini döndürür.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| val | long | Enum constant'ın değeri |

### Dönüş Değeri

**str** içinde belirtilen değerin enum constant'ının kutulanmış değeri.

## Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)