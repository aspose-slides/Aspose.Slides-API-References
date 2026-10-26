---
title: Enum
second_title: Aspose.Slides for C++ API Referansı
description: Enum tipindeki değerler üzerinde bazı işlemler gerçekleştiren metodlar sağlar. Bu, örnek hizmeti bulunmayan statik bir tiptir. Onu hiçbir şekilde örnek oluşturarak kullanmamalısınız.
type: docs
weight: 1587
url: /tr/system/enum/
---
## Enum yapısı

Enum tipindeki değerler üzerinde bazı işlemler gerçekleştiren metodlar sağlar. Bu, örnek hizmetleri olmayan statik bir tiptir. Onu hiçbir şekilde örnek oluşturmamalısınız.

```cpp
template<class E,class Guard>class Enum
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| E | Sınıfın işlediği değerlerin enum türü |
| Guard | **E**'nin enum tipinde olduğundan emin olmak amacıyla kullanılan hizmet tipi argümanı |

## Metodlar

| Metod | Açıklama |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Belirtilen enum sabitlerinin değerlerinin aritmetik karşılaştırmasını gerçekleştirir. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Belirtilen değere sahip enum sabitinin adını döndürür. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Belirtilen değere sahip enum sabitinin adını döndürür. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Enum **E**'nin tüm üyelerinin adlarını içeren bir dizi döndürür. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Enumun temel tipini döndürür. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Enum **E**'nin tüm üyelerini içeren bir dizi döndürür. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Belirtilen enum değerinin bit dizimi temsilinde belirtilen bitlerin ayarlanıp ayarlanmadığını belirler. |
| static **bool** [IsDefined](./isdefined/)(E) | Belirtilen değerin enum tipi **E**'nin bir üyesi olup olmadığını belirler. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Belirtilen değerin enum tipi **T**'nin bir üyesi olup olmadığını belirler. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Belirtilen isimdeki değerin enum **E** üyeleri arasında olup olmadığını belirler. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Belirtilen dizeyi eşdeğer enum sabitine dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Belirtilen dizeyi eşdeğer enum sabitine dönüştürmeyi dener. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Belirtilen dizeyi eşdeğer enum sabitine dönüştürmeyi dener. |

## Typedef'ler

| Tip Tanımı | Açıklama |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Enumun temel tipinin takma adı. |

## Ayrıca Bakınız

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)