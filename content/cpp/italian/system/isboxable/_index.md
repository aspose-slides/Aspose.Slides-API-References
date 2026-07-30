---
title: IsBoxable
second_title: Riferimento API Aspose.Slides per C++
description: Predicato template che verifica se il boxing del tipo specificato è supportato.
type: docs
weight: 1665
url: /it/system/isboxable/
---
## IsBoxable struct

Predicato template che verifica se il boxing del tipo specificato è supportato.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo da verificare |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)