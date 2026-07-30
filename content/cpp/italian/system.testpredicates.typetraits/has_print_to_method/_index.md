---
title: has_print_to_method
second_title: Riferimento API Aspose.Slides per C++
description: "Verifica la presenza di un overload della funzione PrintTo che accetta il tipo fornito come primo argomento. Se esiste un overload, eredita std::true_type, altrimenti eredita std::false_type."
type: docs
weight: 27
url: /it/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Verifica la presenza di un overload della funzione PrintTo che accetta il tipo fornito come primo argomento. Se esiste un overload, eredita std::true_type, altrimenti eredita std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Parametri template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo da verificare. |
| Enable | Argomento formale per far funzionare SFINAE. |

## Vedi anche

* Spazio dei nomi [System::TestPredicates::TypeTraits](../)
* Libreria [Aspose.Slides](../../)