---
title: ComparerType
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht Elemente mit 'less'-Semantik.
type: docs
weight: 144
url: /de/system.collections.generic.details/comparertype/
---
## ComparerType struct

Vergleicht Elemente mit 'less'-Semantik.

```cpp
template<typename T>class ComparerType
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ der zu vergleichenden Elemente. |

## Methoden

| Method | Beschreibung |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Vergleicht Werttypen, die das Interface [IComparable](../../system/icomparable/) implementieren. |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Vergleicht primitive Werttypen und Objekte, die das Interface [IComparable](../../system/icomparable/) nicht implementieren. |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Vergleicht Gleitkommatypen. |

## Siehe auch

* Namensraum [System::Collections::Generic::Details](../)
* Bibliothek [Aspose.Slides](../../)