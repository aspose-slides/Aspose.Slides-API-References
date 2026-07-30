---
title: IsCppContainer
second_title: Riferimento API di Aspose.Slides per C++
description: "Verifica se un tipo specifico è un contenitore in stile STL. Per farlo, verifica l'esistenza dei tipi membro iterator e const_iterator. Se entrambi esistono, eredita std::true_type, altrimenti eredita std::false_type."
type: docs
weight: 40
url: /it/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Verifica se un tipo specifico è un contenitore in stile STL. Per farlo, controlla l'esistenza dei tipi membro iterator e const_iterator. Se entrambi esistono, eredita std::true_type, altrimenti eredita std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo da verificare. |
| Enable | Argomento formale per far funzionare SFINAE. |

## Vedi anche

* Namespace [System::TestPredicates::TypeTraits](../)
* Libreria [Aspose.Slides](../../)