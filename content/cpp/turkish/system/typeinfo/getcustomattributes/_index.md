---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API Referansı
description: türe uygulanan tüm özel öznitelikleri temsil eden nesneleri içeren bir dizi döndürür.
type: docs
weight: 586
url: /tr/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const metod


Tüm özelleştirilmiş özniteliklerin tür üzerine uygulanmasını temsil eden nesneleri içeren bir dizi döndürür.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const metod


Belirli özniteliklerin tür üzerine uygulanmasını temsil eden nesneleri içeren bir dizi döndürür.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Aranacak öznitelik türü. |
| inherit | **bool** | Kalıtılmış özniteliklerin de aranıp aranmayacağını belirtir. |

## Bkz.

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [SmartPtr](../../smartptr/)
* Sınıf [TypeInfo](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)