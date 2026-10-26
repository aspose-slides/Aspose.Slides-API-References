---
title: ComparerAdapter
second_title: Aspose.Slides voor C++ API-referentie
description: Adapter om IComparer te gebruiken binnen de STL-omgeving. Gebruikt IComparer indien ingesteld; anders gebruikt het operator < (indien beschikbaar) of retourneert false (indien niet).
type: docs
weight: 638
url: /nl/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adapter om [IComparer](../icomparer/) te gebruiken binnen de STL-omgeving. Gebruikt [IComparer](../icomparer/) indien ingesteld; anders gebruikt het operator < (indien beschikbaar) of retourneert false (indien niet).

```cpp
template<class T>class ComparerAdapter
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type dat wordt vergeleken. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Construeert een adapter zonder beschikbare comparator. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Construeert een adapter. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) functie voor typen met operator < beschikbaar. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) functie voor typen zonder operator < beschikbaar. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Stelt comparatorobject in. |

## Zie ook

* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)