---
title: HolderInitializer< T, false >
second_title: Aspose.Slides voor C++ API-referentie
description: HolderInitializer-specialisatie voor het geval dat T een waardetype is. De gebruikscontext staat toe om een referentie naar tijdelijke objecten terug te geven, aangezien gegarandeerd is dat het exemplaar door de aanroeper wordt gekopieerd. Daarom wordt deze specialisatie alleen als een stub gebruikt en doet niets.
type: docs
weight: 1652
url: /nl/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct

[HolderInitializer](../holderinitializer/) specialisatie voor het geval dat T een waardetype is. De gebruikscontext staat toe om een referentie naar tijdelijke objecten terug te geven, aangezien het gegarandeerd is dat het exemplaar door de aanroeper gekopieerd zal worden. Daarom wordt deze specialisatie alleen als een stub gebruikt en doet niets.

```cpp
template<typename T>class HolderInitializer< T, false >
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |
## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)