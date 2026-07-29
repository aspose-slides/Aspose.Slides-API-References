---
title: setter_increment_wrap()
second_title: Aspose.Slides för C++ API-referens
description: Översättaren översätter C#'s inkrementuttryck som riktar sig mot klassens egenskap som har setter och getter definierade, till anrop av denna funktion.
type: docs
weight: 2835
url: /sv/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) funktion

Översättaren översätter C#-s inkrementuttryck som riktar sig mot klassens egenskap som har setter och getter definierade, till anrop av denna funktion.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av egenskapen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pGetter | T(*)() | Funktionspekare som pekar på egenskapens getter-fria funktion |
| pSetter | void(*)(T) | Funktionspekare som pekar på egenskapens setter-fria funktion |

### Returvärde

Det inkrementerade värdet av egenskapen

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) funktion

Översättaren översätter C#-s inkrementuttryck som riktar sig mot klassens egenskap som har setter och getter definierade, till anrop av denna funktion.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av egenskapen |
| Host | - klass för instansen som ska modifieras |
| HostGet | - Host själv, eller dess basklass, där egenskapens getter är definierad |
| HostSet | - Host själv, eller dess basklass, där egenskapens setter är definierad |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | Host *const | En pekare till ett objekt vars egenskap ska inkrementeras |
| pGetter | T(HostGet::*)() | Funktionspekare som pekar på egenskapens getter-metod |
| pSetter | void(HostSet::*)(T) | Funktionspekare som pekar på egenskapens setter-metod |

### Returvärde

Det inkrementerade värdet av egenskapen

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)