---
title: ComparerType
second_title: Aspose.Slides för C++ API-referens
description: Jämför element med 'less'-semantik.
type: docs
weight: 144
url: /sv/system.collections.generic.details/comparertype/
---
## ComparerType struct

Jämför element med 'less'-semantik.

```cpp
template<typename T>class ComparerType
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av jämförda element. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Jämför värdetyper som implementerar [IComparable](../../system/icomparable/)-gränssnittet. |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Jämför primitiva värdetyper och objekt som inte implementerar [IComparable](../../system/icomparable/)-gränssnittet. |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Jämför flyttalstyper. |

## Se även

* Namnrymd [System::Collections::Generic::Details](../)
* Bibliotek [Aspose.Slides](../../)