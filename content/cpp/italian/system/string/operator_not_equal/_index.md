---
title: operator!=()
second_title: Riferimento API di Aspose.Slides per C++
description: Operatore di confronto di non uguaglianza.
type: docs
weight: 313
url: /it/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const metodo


Operatore di confronto di non uguaglianza.

```cpp
bool System::String::operator!=(const String &str) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) da confrontare con quello corrente. |

### Valore restituito

false se entrambe le stringhe sono null o entrambe non sono null e corrispondono, true altrimenti.

## String::operator!=(std::nullptr_t) const metodo


Verifica se la stringa non è null. Applica la stessa logica della chiamata [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```


### Valore restituito

false se la stringa è null, true altrimenti.

## Vedi anche

* Classe [String](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)