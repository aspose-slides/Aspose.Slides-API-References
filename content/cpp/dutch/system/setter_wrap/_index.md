---
title: setter_wrap()
second_title: Aspose.Slides voor C++ API-referentie
description: Overload voor statische setter-functies met typeconversie.
type: docs
weight: 2822
url: /nl/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) functie

Overload voor statische setter-functies met typeconversie.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Waardetype. |
| T2 | Type verwacht door setter-functie. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pSetter | void(*)(T2) | Referentie naar statische setter-functie. |
| value | T | Waarde om in te stellen. |

### Returnwaarde

waarde ingesteld.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) functie

Overload voor instantie setter-functies met typeconversie.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Waardetype. |
| T2 | Type verwacht door setter-functie. |
| Host | Instantietype. |
| HostSet | - Host zelf, of het basistype, waarin de setter van de eigenschap is gedefinieerd. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | Host *const | [Object](../object/) om setter-functie aan te roepen voor. |
| pSetter | void(HostSet::*)(T2) | Referentie naar setter-functie. |
| value | T | Waarde om in te stellen. |

### Returnwaarde

waarde ingesteld.

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)