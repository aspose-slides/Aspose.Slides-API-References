---
title: Build()
second_title: Riferimento API Aspose.Slides per C++
description: Costruisci un oggetto con proprietà diretta.
type: docs
weight: 2289
url: /it/system/build/
---
## System::Build(Args\&&...) funzione

Costruisci un oggetto con proprietà diretta.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di oggetto da costruire |
| Args | Tipi degli argomenti per la costruzione dell'oggetto |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | Args\&&... | Argomenti da inoltrare al costruttore dell'oggetto |

### Valore di ritorno

ObjectBuilder configurato per la costruzione diretta dell'oggetto

## Note



[Object](../object/) la costruzione deve essere completata con la chiamata [Get()](../get/)

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)