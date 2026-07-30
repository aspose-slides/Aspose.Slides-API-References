---
title: what()
second_title: Riferimento API di Aspose.Slides per C++
description: "Implementa il metodo what() che è chiamato dalla classe ExceptionWrapper. Nonostante il fatto che questa classe non erediti da std::exception, le classi derivate possono utilizzare membri protetti/private per implementare la loro logica. Spostare l'implementazione di questo metodo nella classe ExceptionWrapper potrebbe compromettere tale logica."
type: docs
weight: 105
url: /it/system/details_exception/what/
---
## Details_Exception::what() const metodo


Implementa [what()](./) metodo che è chiamato dalla classe [ExceptionWrapper](../../exceptionwrapper/). Nonostante il fatto che questa classe non erediti da std::exception, le classi derivate possono usare membri protetti/private per implementare la loro logica. Spostare l'implementazione di questo metodo nel [ExceptionWrapper](../../exceptionwrapper/) potrebbe rompere quella logica.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```


### Valore di ritorno

La descrizione dell'eccezione.

## Vedi anche

* Classe [Details_Exception](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)