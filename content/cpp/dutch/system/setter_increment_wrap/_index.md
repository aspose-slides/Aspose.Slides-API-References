---
title: setter_increment_wrap()
second_title: Aspose.Slides voor C++ API-referentie
description: Vertaler zet C#-incrementexpressies die gericht zijn op de eigenschap van een klasse met een setter en getter, om in een aanroep van deze functie.
type: docs
weight: 2835
url: /nl/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) functie


Vertaler zet C#-incrementexpressies die gericht zijn op de eigenschap van een klasse met een setter en getter, om in een aanroep van deze functie.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de eigenschap |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pGetter | T(*)() | Functie-pointer die verwijst naar de getter-functie van de eigenschap |
| pSetter | void(*)(T) | Functie-pointer die verwijst naar de setter-functie van de eigenschap |

### Retourwaarde

De verhoogde waarde van de eigenschap

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) functie


Vertaler zet C#-incrementexpressies die gericht zijn op de eigenschap van een klasse met een setter en getter, om in een aanroep van deze functie.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de eigenschap |
| Host | - klasse van instantie die moet worden aangepast |
| HostGet | - Host zelf, of zijn basistype, waar de getter van de eigenschap is gedefinieerd |
| HostSet | - Host zelf, of zijn basistype, waar de setter van de eigenschap is gedefinieerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | Host *const | Een pointer naar een object waarvan de eigenschap moet worden verhoogd |
| pGetter | T(HostGet::*)() | Functie-pointer die verwijst naar de getter-methode van de eigenschap |
| pSetter | void(HostSet::*)(T) | Functie-pointer die verwijst naar de setter-methode van de eigenschap |

### Retourwaarde

De verhoogde waarde van de eigenschap

## Zie Ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)