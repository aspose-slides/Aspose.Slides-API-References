---
title: setter_wrap()
second_title: Aspose.Slides för C++ API-referens
description: Överlagring för statiska setter-funktioner med typkonvertering.
type: docs
weight: 2822
url: /sv/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) funktion

Överlagring för statiska setter-funktioner med typkonvertering.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |
| T2 | Typ som förväntas av setter-funktion. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pSetter | void(*)(T2) | Statisk setter-funktionsreferens. |
| value | T | Värde att sätta. |

### Returvärde

sätt värde.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) funktion

Överlagring för instanssetter-funktioner med typkonvertering.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |
| T2 | Typ som förväntas av setter-funktion. |
| Host | Instanstyp. |
| HostSet | - Host själv, eller dess basklass, där egendomens setter är definierad. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | Host *const | [Object](../object/) att anropa setter-funktion för. |
| pSetter | void(HostSet::*)(T2) | Setter-funktionsreferens. |
| value | T | Värde att sätta. |

### Returvärde

sätt värde.

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)