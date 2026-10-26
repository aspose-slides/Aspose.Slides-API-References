---
title: ComparerType
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Porównuje elementy używając semantyki 'less'.
type: docs
weight: 144
url: /pl/system.collections.generic.details/comparertype/
---
## ComparerType struct

Porównuje elementy używając semantyki 'less'.

```cpp
template<typename T>class ComparerType
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ porównywanych elementów. |
## Metody

| Metoda | Opis |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Porównuje typy wartości implementujące interfejs [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Porównuje prymitywne typy wartości oraz obiekty nieimplementujące interfejsu [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Porównuje typy zmiennoprzecinkowe. |

## Zobacz też

* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)