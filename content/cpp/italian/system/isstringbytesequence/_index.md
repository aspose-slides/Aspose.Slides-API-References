---
title: IsStringByteSequence
second_title: Riferimento API di Aspose.Slides per C++
description: Magia del template per verificare se un tipo è una sequenza di caratteri stringa.
type: docs
weight: 1717
url: /it/system/isstringbytesequence/
---
## IsStringByteSequence struct

Magia del template per verificare se un tipo è una sequenza di caratteri stringa.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | tipo controllato. |
| CharT | Tipo di carattere da confrontare. |

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)