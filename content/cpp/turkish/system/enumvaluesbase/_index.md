---
title: EnumValuesBase
second_title: Aspose.Slides for C++ API Referansı
description: Enumeration tipinin meta bilgisini temsil eden bir sınıf için temel sınıftır.
type: docs
weight: 807
url: /tr/system/enumvaluesbase/
---
## EnumValuesBase sınıfı


Enumeration tipinin meta bilgisini temsil eden bir sınıf için temel sınıftır.

```cpp
class EnumValuesBase
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Belirtilen bir enumeration içindeki sabitlerin adlarını içeren bir dizi alır. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Belirtilen enumeration'ın temel tipini döndürür. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Belirtilen enumeration türünün tüm değerlerini içeren bir dizi döndürür. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Belirtilen adıyla belirtilen enumeration türünün sabit değerini temsil eden bir nesne döndürür. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Belirtilen 64 bit işaretsiz tamsayı değerini bir enumeration üyesine dönüştürür. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Belirtilen tam sayı değerine sahip nesneyi bir enumeration üyesine dönüştürür. |
## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)