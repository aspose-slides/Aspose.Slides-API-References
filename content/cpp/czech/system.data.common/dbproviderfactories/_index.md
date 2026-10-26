---
title: DbProviderFactories
second_title: Aspose.Slides pro C++ API Reference
description: "API pro získání DB provider factories. Objektům této třídy by mělo být přiřazováno pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání funkcím jako argument."
type: docs
weight: 53
url: /cs/system.data.common/dbproviderfactories/
---
## DbProviderFactories třída

API pro získání DB provider factories. Objektům této třídy by mělo být přiřazováno pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání funkcím jako argument.

```cpp
class DbProviderFactories
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Získá DB provider factory podle názvu. |

## Viz také

* Jmenný prostor [System::Data::Common](../)
* Knihovna [Aspose.Slides](../../)