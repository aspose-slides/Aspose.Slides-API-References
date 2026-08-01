---
title: Ref()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een referentie naar een DynamicWeakPtr-object. Wordt door de vertaler gebruikt bij het doorgeven van functie-argumenten per referentie.
type: docs
weight: 2458
url: /nl/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) functie


Creëert een referentie naar het [DynamicWeakPtr](../dynamicweakptr/)-object. Wordt door de vertaler gebruikt bij het doorgeven van functie-argumenten per referentie.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Pointee-type. |
| trunkMode | Modus van de smart-pointer zelf. |
| weakLeafs | Indexen van sjabloon-argumenten waarvoor de SetTemplateWeakPtr-methode moet worden aangeroepen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Smart-pointer om een referentie naar te maken. |

### Retourwaarde

Smart-pointer referentie.

## System::Ref(T\&) functie


Helper-functie om referenties naar objecten te verkrijgen. Wordt gebruikt om te garanderen dat [System::DynamicWeakPtr](../dynamicweakptr/) het gerefereerde object na toewijzingen bijwerkt.

```cpp
template<typename T> T & System::Ref(T &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type om een referentie naar te maken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T\& | Waarde om een referentie naar te maken. |

### Retourwaarde

Referentie naar de waarde die aan deze functie is doorgegeven.

## Zie ook

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)