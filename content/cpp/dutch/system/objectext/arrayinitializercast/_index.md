---
title: ArrayInitializerCast()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert fundamentele arraywaarden (wat C# impliciet doet, maar C++ blijkbaar niet).
type: docs
weight: 209
url: /nl/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) methode

Converteert fundamentele arraywaarden (wat C# impliciet doet, maar C++ blijkbaar niet).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| To | Doeltype. |
| From | Bron-types. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | From ... | Waarden die moeten worden geconverteerd en naar de doelarray worden gepusht. |

### Retourwaarde

[Array](../../array/) met geconverteerde kopieën van alle argumenten in dezelfde volgorde.

## Zie ook

* Klasse [ObjectExt](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)