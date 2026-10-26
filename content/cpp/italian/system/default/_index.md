---
title: Default()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il riferimento all'unica istanza costruita con il costruttore predefinito del tipo di eccezione.
type: docs
weight: 2224
url: /it/system/default/
---
## System::Default() funzione


Restituisce il riferimento all'unica istanza costruita con il costruttore predefinito del tipo di eccezione.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo la cui istanza è restituita |

## System::Default() funzione


Restituisce il riferimento all'unica istanza costruita con il costruttore predefinito del tipo non eccezione.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo la cui istanza è restituita |

## Vedi anche

* Struttura [IsExceptionWrapper](../isexceptionwrapper/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)