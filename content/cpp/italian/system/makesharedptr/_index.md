---
title: MakeSharedPtr()
second_title: Aspose.Slides per C++ Riferimento API
description: Converte un puntatore grezzo in un puntatore intelligente.
type: docs
weight: 2900
url: /it/system/makesharedptr/
---
## System::MakeSharedPtr(X *) funzione


Converte un puntatore grezzo in un puntatore intelligente.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo dell'oggetto puntato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | X * | Puntatore grezzo all'oggetto. |

### Valore restituito

Puntatore intelligente condiviso all'oggetto.

## System::MakeSharedPtr(const X *) funzione


Converte un puntatore grezzo in un puntatore intelligente. Sovraccarico per puntatori const. Utile, ad esempio, quando si utilizza la variabile 'this' nei metodi C# tradotti come const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo dell'oggetto puntato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | const X * | Puntatore grezzo all'oggetto. |

### Valore restituito

Puntatore intelligente condiviso all'oggetto.

## Vedi anche

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)