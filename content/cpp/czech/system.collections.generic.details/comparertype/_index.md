---
title: ComparerType
second_title: Aspose.Slides pro C++ – reference API
description: Porovnává prvky pomocí sémantiky 'less'.
type: docs
weight: 144
url: /cs/system.collections.generic.details/comparertype/
---
## ComparerType struct

Porovnává prvky pomocí sémantiky 'less'.

```cpp
template<typename T>class ComparerType
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ porovnávaných prvků. |

## Metody

| Metoda | Popis |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Porovnává typy hodnot implementující rozhraní [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Porovnává primitivní typy hodnot a objekty neimplementující rozhraní [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Porovnává typy s plovoucí desetinnou čárkou. |

## Viz také

* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)