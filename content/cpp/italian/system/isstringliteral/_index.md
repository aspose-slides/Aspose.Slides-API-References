---
title: IsStringLiteral
second_title: Riferimento API di Aspose.Slides per C++
description: Magia dei template per verificare se un tipo è un letterale stringa.
type: docs
weight: 1730
url: /it/system/isstringliteral/
---
## IsStringLiteral struct

Magia dei template per verificare se un tipo è un letterale stringa.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | tipo controllato. |
| CharT | Tipo di carattere contro cui verificare. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)