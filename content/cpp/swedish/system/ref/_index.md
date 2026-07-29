---
title: Ref()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en referens till DynamicWeakPtr-objektet. Används av översättaren när funktionsargument skickas som referens.
type: docs
weight: 2458
url: /sv/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) funktion


Skapar en referens till [DynamicWeakPtr](../dynamicweakptr/)-objektet. Används av översättaren när funktionsargument skickas som referens.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen som pekas på. |
| trunkMode | Läge för smartpekaren själv. |
| weakLeafs | Index för mallargument som SetTemplateWeakPtr-metoden måste anropas för. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Smartpekare att skapa referens till. |

### Returvärde

Smart pekarreferens.

## System::Ref(T\&) funktion


Hjälpfunktion för att erhålla referenser till objekt. Används för att säkerställa att [System::DynamicWeakPtr](../dynamicweakptr/) uppdaterar det refererade objektet efter tilldelningar.

```cpp
template<typename T> T & System::Ref(T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att skapa referens till. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T\& | Värde att skapa referens till. |

### Returvärde

Referens till värdet som skickas till denna funktion.

## Se även

* Klass [DynamicWeakPtr](../dynamicweakptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)