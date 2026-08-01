---
title: setter_post_increment_wrap()
second_title: Aspose.Slides voor C++ API-referentie
description: De vertaler vertaalt C#'s post-increment-expressies die gericht zijn op de eigenschap van een klasse die een setter en getter heeft gedefinieerd, naar een aanroep van deze functie.
type: docs
weight: 2848
url: /nl/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) functie

Vertaler vertaalt C#-post-increment-expressies die gericht zijn op de eigenschap van een klasse die een setter en getter heeft gedefinieerd, naar een aanroep van deze functie.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de eigenschap |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pGetter | T(*)() | Functiepointer die naar de vrije functie van de getter van de eigenschap wijst |
| pSetter | void(*)(T) | Functiepointer die naar de vrije functie van de setter van de eigenschap wijst |

### Retourwaarde

De waarde van de eigenschap vóór het verhogen

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) functie

Vertaler vertaalt C#-post-increment-expressies die gericht zijn op de eigenschap van een instantie die een setter en getter heeft gedefinieerd, naar een aanroep van deze functie (overload voor niet-const getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de eigenschap. |
| Host | - klasse van de instantie die moet worden aangepast |
| HostGet | - Host zelf, of zijn basistype, waarin de getter van de eigenschap is gedefinieerd |
| HostSet | - Host zelf, of zijn basistype, waarin de setter van de eigenschap is gedefinieerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | Host *const | Instantie waarvoor getters en setters worden aangeroepen. |
| pGetter | T(HostGet::*)() | Functiepointer die naar de getter-functie van de eigenschap wijst |
| pSetter | void(HostSet::*)(T) | Functiepointer die naar de setter-functie van de eigenschap wijst |

### Retourwaarde

De waarde van de eigenschap vóór het verhogen

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) functie

Vertaler vertaalt C#-post-increment-expressies die gericht zijn op de eigendom van een instantie die een setter en getter heeft gedefinieerd, naar een aanroep van deze functie (overload voor const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de eigenschap. |
| Host | - klasse van de instantie die moet worden aangepast |
| HostConstGet | - Host zelf, of zijn basistype, waarin de getter van de eigenschap is gedefinieerd |
| HostSet | - Host zelf, of zijn basistype, waarin de setter van de eigenschap is gedefinieerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | Host *const | Instantie waarvoor getters en setters worden aangeroepen. |
| pGetter | T(HostConstGet::*)() const | Functiepointer die naar de getter-functie van de eigenschap wijst |
| pSetter | void(HostSet::*)(T) | Functiepointer die naar de setter-functie van de eigenschap wijst |

### Retourwaarde

De waarde van de eigenschap vóór het verhogen

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)