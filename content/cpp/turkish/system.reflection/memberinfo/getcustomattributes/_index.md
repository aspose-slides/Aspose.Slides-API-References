---
title: GetCustomAttributes()
second_title: Aspose.Slides için C++ API Referansı
description: Geçerli nesne tarafından temsil edilen türe uygulanan tüm özel nitelikleri temsil eden nesneleri içeren bir dizi döndürür.
type: docs
weight: 66
url: /tr/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const metod


Geçerli nesne tarafından temsil edilen türe uygulanan tüm özel nitelikleri temsil eden nesneleri içeren bir dizi döndürür.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Aranacak nitelik tipi. |
| inherit | **bool** | Miras alınan niteliklerin de kontrol edilip edilmediği. |

## MemberInfo::GetCustomAttributes(bool) const metod


Geçerli nesne tarafından temsil edilen türe uygulanan tüm özel nitelikleri temsil eden nesneleri içeren bir dizi döndürür.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inherit | **bool** | Miras alınan niteliklerin de kontrol edilip edilmediği. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [MemberInfo](../)
* Ad alanı [System::Reflection](../../)
* Kütüphane [Aspose.Slides](../../../)