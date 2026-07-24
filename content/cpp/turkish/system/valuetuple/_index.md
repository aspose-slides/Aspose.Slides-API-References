---
title: ValueTuple
second_title: Aspose.Slides for C++ API Referansı
description: ValueTuple veri yapısını temsil eden sınıf.
type: docs
weight: 1444
url: /tr/system/valuetuple/
---
## ValueTuple sınıfı

Veri yapısını temsil eden bir [ValueTuple](./) sınıfı.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Geçerli ve belirtilen nesnelerin aynı olup olmadığını belirler. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | [ValueTuple](./) nesnesinin bileşeninin değerine referansı alır. |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | [ValueTuple](./) nesnesinin bileşeninin değerini alır. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Nesneyi bu değer demetine ayırır. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [ValueTuple](./) sınıfı türü bilgisini temsil eden [TypeInfo](../typeinfo/) nesnesine bir referans döndürür. |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Bir demet nesnesi oluşturur. |

## Ayrıca Bakınız

* İsim Uzayı [System](../)
* Kütüphane [Aspose.Slides](../../)