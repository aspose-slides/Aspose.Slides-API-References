---
title: setter_wrap()
second_title: Riferimento API di Aspose.Slides per C++
description: Sovraccarico per funzioni setter statiche con conversione di tipo.
type: docs
weight: 2822
url: /it/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) funzione

Sovraccarico per funzioni setter statiche con conversione di tipo.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di valore. |
| T2 | Tipo previsto dalla funzione setter. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pSetter | void(*)(T2) | Riferimento a funzione setter statica. |
| value | T | Valore da impostare. |

### Valore restituito

imposta il valore.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) funzione

Sovraccarico per funzioni setter di istanza con conversione di tipo.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di valore. |
| T2 | Tipo previsto dalla funzione setter. |
| Host | Tipo di istanza. |
| HostSet | - Host stesso, o il suo tipo base, dove è definito il setter della proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | Host *const | [Object](../object/) per chiamare la funzione setter. |
| pSetter | void(HostSet::*)(T2) | Riferimento alla funzione setter. |
| value | T | Valore da impostare. |

### Valore restituito

imposta il valore.

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)