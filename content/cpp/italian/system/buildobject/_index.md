---
title: BuildObject()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisci un oggetto con possesso condiviso.
type: docs
weight: 2250
url: /it/system/buildobject/
---
## System::BuildObject(Args\&&...) funzione


Costruisci un oggetto con possesso condiviso.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'oggetto da costruire |
| Args | Tipi degli argomenti per la costruzione dell'oggetto |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | Args\&&... | Argomenti da inoltrare al costruttore dell'oggetto |

### Valore restituito

ObjectBuilder configurato per la costruzione di shared pointer
## Osservazioni



Crea un SharedPtr<T> e restituisce un builder per esso 
[Object](../object/) la costruzione deve essere completata con la chiamata [Get()](../get/) 

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)