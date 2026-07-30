---
title: setter_post_increment_wrap()
second_title: Riferimento API di Aspose.Slides per C++
description: Il traduttore traduce le espressioni post-incremento di C# che hanno come obiettivo la proprietà di una classe con setter e getter definiti, in una chiamata a questa funzione.
type: docs
weight: 2848
url: /it/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) funzione


Il traduttore traduce le espressioni post-incremento di C# che hanno come obiettivo la proprietà di una classe con setter e getter definiti, in una chiamata a questa funzione.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo della proprietà |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pGetter | T(*)() | Puntatore a funzione che punta alla funzione libera getter della proprietà |
| pSetter | void(*)(T) | Puntatore a funzione che punta alla funzione libera setter della proprietà |

### Valore restituito

Il valore della proprietà prima dell’incremento

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) funzione


Il traduttore traduce le espressioni post-incremento di C# che hanno come obiettivo la proprietà di un’istanza con setter e getter definiti, in una chiamata a questa funzione (sovraccarico per getter non costante).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo della proprietà. |
| Host | - classe dell’istanza da modificare |
| HostGet | - Host stesso, o il suo tipo base, dove è definito il getter della proprietà |
| HostSet | - Host stesso, o il suo tipo base, dove è definito il setter della proprietà |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | Host *const | Istanza su cui chiamare getter e setter. |
| pGetter | T(HostGet::*)() | Puntatore a funzione che punta alla funzione getter della proprietà |
| pSetter | void(HostSet::*)(T) | Puntatore a funzione che punta alla funzione setter della proprietà |

### Valore restituito

Il valore della proprietà prima dell’incremento

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) funzione


Il traduttore traduce le espressioni post-incremento di C# che hanno come obiettivo la proprietà di un’istanza con setter e getter definiti, in una chiamata a questa funzione (sovraccarico per getter costante).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo della proprietà. |
| Host | - classe dell’istanza da modificare |
| HostConstGet | - Host stesso, o il suo tipo base, dove è definito il getter della proprietà |
| HostSet | - Host stesso, o il suo tipo base, dove è definito il setter della proprietà |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | Host *const | Istanza su cui chiamare getter e setter. |
| pGetter | T(HostConstGet::*)() const | Puntatore a funzione che punta alla funzione getter della proprietà |
| pSetter | void(HostSet::*)(T) | Puntatore a funzione che punta alla funzione setter della proprietà |

### Valore restituito

Il valore della proprietà prima dell’incremento

## Vedi anche

* Namespace [System](../)
* Library [Aspose.Slides](../../)