---
title: setter_decrement_wrap()
second_title: Riferimento API Aspose.Slides per C++
description: Il traduttore converte le espressioni pre-decremento di C# che hanno come obiettivo la proprietà di una classe con setter e getter definiti, in una chiamata a questa funzione.
type: docs
weight: 2861
url: /it/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) function

Il traduttore converte le espressioni pre-decremento di C# che hanno come obiettivo la proprietà di una classe con setter e getter definiti, in una chiamata a questa funzione.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo della proprietà |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Puntatore a funzione che indica il getter libero della proprietà |
| pSetter | void(*)(T) | Puntatore a funzione che indica il setter libero della proprietà |

### Valore di ritorno

Il valore della proprietà prima del decremento

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function

Il traduttore converte le espressioni pre-decremento di C# che hanno come obiettivo la proprietà di un'istanza con setter e getter definiti, in una chiamata a questa funzione (sovraccarico per getter non const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo della proprietà. |
| Host | - classe dell'istanza da modificare |
| HostGet | - Host stesso, o il suo tipo base, dove è definito il getter della proprietà |
| HostSet | - Host stesso, o il suo tipo base, dove è definito il setter della proprietà |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Istanza su cui chiamare i getter e i setter. |
| pGetter | T(HostGet::*)() | Puntatore a funzione che indica il getter della proprietà |
| pSetter | void(HostSet::*)(T) | Puntatore a funzione che indica il setter della proprietà |

### Valore di ritorno

Il valore della proprietà prima del decremento

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function

Il traduttore converte le espressioni pre-decremento di C# che hanno come obiettivo la proprietà di un'istanza con setter e getter definiti, in una chiamata a questa funzione (sovraccarico per getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo della proprietà. |
| Host | - classe dell'istanza da modificare |
| HostConstGet | - Host stesso, o il suo tipo base, dove è definito il getter della proprietà |
| HostSet | - Host stesso, o il suo tipo base, dove è definito il setter della proprietà |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Istanza su cui chiamare i getter e i setter. |
| pGetter | T(HostConstGet::*)() const | Puntatore a funzione che indica il getter della proprietà |
| pSetter | void(HostSet::*)(T) | Puntatore a funzione che indica il setter della proprietà |

### Valore di ritorno

Il valore della proprietà prima del decremento

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)