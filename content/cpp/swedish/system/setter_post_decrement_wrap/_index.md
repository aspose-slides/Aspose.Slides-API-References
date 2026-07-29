---
title: setter_post_decrement_wrap()
second_title: Aspose.Slides för C++ API-referens
description: Översättaren översätter C#'s postdekrementuttryck som riktar sig mot klassens egenskap som har setter och getter definierade, till anrop av denna funktion.
type: docs
weight: 2874
url: /sv/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) function


Översättaren översätter C#-s postdekrementuttryck som riktar sig mot klassens egenskap som har setter och getter definierade, till anrop av den här funktionen.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av egenskapen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pGetter | T(*)() | Funktionspekare som pekar på egenskapens getter-fri funktion |
| pSetter | void(*)(T) | Funktionspekare som pekar på egenskapens setter-fri funktion |

### Returvärde

Värdet på egenskapen före inkrementering

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function


Översättaren översätter C#-s postdekrementuttryck som riktar sig mot instansens egenskap som har setter och getter definierade, till anrop av den här funktionen (överladdning för icke-konstant getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av egenskapen. |
| Host | - klass av instans som ska modifieras |
| HostGet | - Host själv, eller dess basklass, där egenskapens getter är definierad |
| HostSet | - Host själv, eller dess basklass, där egenskapens setter är definierad |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | Host *const | Instans att anropa getters och setters för. |
| pGetter | T(HostGet::*)() | Funktionspekare som pekar på egenskapens getter-funktion |
| pSetter | void(HostSet::*)(T) | Funktionspekare som pekar på egenskapens setter-funktion |

### Returvärde

Värdet på egenskapen före inkrementering

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function


Översättaren översätter C#-s postdekrementuttryck som riktar sig mot instansens egenskap som har setter och getter definierade, till anrop av den här funktionen (överladdning för konstant getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av egenskapen. |
| Host | - klass av instans som ska modifieras |
| HostConstGet | - Host själv, eller dess basklass, där egenskapens getter är definierad |
| HostSet | - Host själv, eller dess basklass, där egenskapens setter är definierad |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | Host *const | Instans att anropa getters och setters för. |
| pGetter | T(HostConstGet::*)() const | Funktionspekare som pekar på egenskapens getter-funktion |
| pSetter | void(HostSet::*)(T) | Funktionspekare som pekar på egenskapens setter-funktion |

### Returvärde

Värdet på egenskapen före inkrementering

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)