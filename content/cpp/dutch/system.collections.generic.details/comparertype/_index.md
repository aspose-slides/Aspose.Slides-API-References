---
title: ComparerType
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt elementen met behulp van 'less' semantiek.
type: docs
weight: 144
url: /nl/system.collections.generic.details/comparertype/
---
## ComparerType struct

Vergelijkt elementen met behulp van 'less' semantiek.

```cpp
template<typename T>class ComparerType
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van vergeleken elementen. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Vergelijkt waardetypen die de [IComparable](../../system/icomparable/)-interface implementeren. |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Vergelijkt primitieve waardetypen en objecten die de [IComparable](../../system/icomparable/)-interface niet implementeren. |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Vergelijkt floating point-typen. |

## Zie ook

* Naamruimte [System::Collections::Generic::Details](../)
* Bibliotheek [Aspose.Slides](../../)