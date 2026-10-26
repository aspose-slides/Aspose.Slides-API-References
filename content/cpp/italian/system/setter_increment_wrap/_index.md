---
title: setter_increment_wrap()
second_title: Riferimento API di Aspose.Slides per C++
description: Il traduttore converte le espressioni di incremento di C# che mirano a una proprietà di classe con setter e getter definiti, in una chiamata a questa funzione.
type: docs
weight: 2835
url: /it/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) funzione

Il traduttore converte le espressioni di incremento di C# che mirano a una proprietà di classe con setter e getter definiti, in una chiamata a questa funzione.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo della proprietà |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pGetter | T(*)() | Puntatore a funzione che indica la funzione libera getter della proprietà |
| pSetter | void(*)(T) | Puntatore a funzione che indica la funzione libera setter della proprietà |

### Valore di ritorno

Il valore incrementato della proprietà

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) funzione

Il traduttore converte le espressioni di incremento di C# che mirano a una proprietà di classe con setter e getter definiti, in una chiamata a questa funzione.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo della proprietà |
| Host | - classe dell'istanza da modificare |
| HostGet | - Host stesso, o il suo tipo base, dove è definito il getter della proprietà |
| HostSet | - Host stesso, o il suo tipo base, dove è definito il setter della proprietà |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | Host *const | Un puntatore a un oggetto la cui proprietà deve essere incrementata |
| pGetter | T(HostGet::*)() | Puntatore a funzione che indica il metodo getter della proprietà |
| pSetter | void(HostSet::*)(T) | Puntatore a funzione che indica il metodo setter della proprietà |

### Valore di ritorno

Il valore incrementato della proprietà

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)