---
title: IsStringPointer
second_title: Riferimento API di Aspose.Slides per C++
description: Magia dei template per verificare se un tipo è un puntatore a stringa di caratteri.
type: docs
weight: 1743
url: /it/system/isstringpointer/
---
## IsStringPointer struct

Magia dei template per verificare se un tipo è un puntatore a stringa di caratteri.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | tipo controllato. |
| CharT | Tipo di carattere da confrontare. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)