---
title: EnumValues
second_title: Aspose.Slides için C++ API Referansı
description: E enum tipinin sabitleri hakkında meta bilgi sağlar.
type: docs
weight: 794
url: /tr/system/enumvalues/
---
## EnumValues sınıfı

enum türü **E**'nin sabitleri hakkında meta bilgi sağlar.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| E | The type of enumeration |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Bir örnek oluşturur. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | **E** enumunun tüm adlarını içeren bir dizi döndürür. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Belirtilen bir enumda sabitlerin adlarını içeren bir dizi alır. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Belirtilen enumun temel tipini döndürür. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Belirtilen enumun temel tipini döndürür. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Belirtilen isimdeki enum sabitinin kutulanmış değerini döndürür. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Belirtilen değerle enum sabitinin kutulanmış değerini döndürür. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | **E** enumunun tüm değerlerini içeren bir dizi döndürür. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Belirtilen enum tipinin tüm değerlerini içeren bir dizi döndürür. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Belirtilen enum tipinin, belirtilen isimdeki sabitinin değerini temsil eden bir nesne döndürür. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Belirtilen 64-bit işaretsiz tamsayı değerini bir enum üyesine dönüştürür. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Belirtilen tamsayı değerine sahip nesneyi bir enum üyesine dönüştürür. |
| virtual  [~EnumValues](./~enumvalues/)() | Yıkıcı. |

## Ayrıca Bakınız

* Sınıf [EnumValuesBase](../enumvaluesbase/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)