---
title: ComparerType
second_title: Aspose.Slides for C++ API Referansı
description: Elemanları 'less' semantiğiyle karşılaştırır.
type: docs
weight: 144
url: /tr/system.collections.generic.details/comparertype/
---
## ComparerType yapı

Elemanları 'less' semantiğiyle karşılaştırır.

```cpp
template<typename T>class ComparerType
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılan elemanların tipi. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [IComparable](../../system/icomparable/) arayüzünü uygulayan değer tiplerini karşılaştırır. |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [IComparable](../../system/icomparable/) arayüzünü uygulamayan ilkel değer tiplerini ve nesneleri karşılaştırır. |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Kayan nokta tiplerini karşılaştırır. |

## İlgili

* Ad alanı [System::Collections::Generic::Details](../)
* Kütüphane [Aspose.Slides](../../)