---
title: setter_decrement_wrap()
second_title: Aspose.Slides voor C++ API-referentie
description: Vertaler vertaalt C#-pre-decrement-expressies die gericht zijn op de eigenschap van een klasse met een setter en getter, naar een aanroep van deze functie.
type: docs
weight: 2861
url: /nl/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) functie

Vertaler vertaalt C#-pre-decrement-expressies die gericht zijn op de eigenschap van een klasse met een setter en getter, naar een aanroep van deze functie.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de eigenschap |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pGetter | T(*)() | Functiewijzer die wijst naar de vrije getter-functie van de eigenschap |
| pSetter | void(*)(T) | Functiewijzer die wijst naar de vrije setter-functie van de eigenschap |

### Retourwaarde

De waarde van de eigenschap vóór het verhogen

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) functie

Vertaler vertaalt C#-pre-decrement-expressies die gericht zijn op de eigenschap van een instantie met een setter en getter, naar een aanroep van deze functie (overload voor niet-const getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de eigenschap. |
| Host | - klasse van de te wijzigen instantie |
| HostGet | - Host zelf, of zijn basistype, waar de getter van de eigenschap is gedefinieerd |
| HostSet | - Host zelf, of zijn basistype, waar de setter van de eigenschap is gedefinieerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | Host *const | Instantie waarvoor getters en setters worden aangeroepen. |
| pGetter | T(HostGet::*)() | Functiewijzer die wijst naar de getter-functie van de eigenschap |
| pSetter | void(HostSet::*)(T) | Functiewijzer die wijst naar de setter-functie van de eigenschap |

### Retourwaarde

De waarde van de eigenschap vóór het verhogen

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) functie

Vertaler vertaalt C#-pre-decrement-expressies die gericht zijn op de eigenschap van een instantie met een setter en getter, naar een aanroep van deze functie (overload voor const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de eigenschap. |
| Host | - klasse van de te wijzigen instantie |
| HostConstGet | - Host zelf, of zijn basistype, waar de getter van de eigenschap is gedefinieerd |
| HostSet | - Host zelf, of zijn basistype, waar de setter van de eigenschap is gedefinieerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | Host *const | Instantie waarvoor getters en setters worden aangeroepen. |
| pGetter | T(HostConstGet::*)() const | Functiewijzer die wijst naar de getter-functie van de eigenschap |
| pSetter | void(HostSet::*)(T) | Functiewijzer die wijst naar de setter-functie van de eigenschap |

### Retourwaarde

De waarde van de eigenschap vóór het verhogen

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)