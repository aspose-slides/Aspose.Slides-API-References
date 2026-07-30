---
title: InitObject()
second_title: Riferimento API di Aspose.Slides per C++
description: Avvia l'inizializzazione di un oggetto con proprietà condivisa.
type: docs
weight: 2263
url: /it/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) funzione

Avvia l'inizializzazione di un oggetto con proprietà condivisa.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di oggetto da inizializzare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) da inizializzare |

### Valore restituito

ObjectBuilder configurato per la costruzione di un puntatore condiviso

## Osservazioni



[Object](../object/) l'inizializzazione deve essere terminata con la chiamata [Get()](../get/)

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)