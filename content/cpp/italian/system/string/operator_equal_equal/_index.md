---
title: operator==()
second_title: Riferimento API di Aspose.Slides per C++
description: Operatore di confronto di uguaglianza.
type: docs
weight: 300
url: /it/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const metodo

Operatore di confronto di uguaglianza.

```cpp
bool System::String::operator==(const String &str) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) per confrontare quello corrente. |

### Valore di ritorno

true se entrambe le stringhe sono null o entrambe non sono null e corrispondono, false altrimenti.

## String::operator==(std::nullptr_t) const metodo

Verifica se la stringa è null. Applica la stessa logica della chiamata [IsNull()](../isnull/).

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### Valore di ritorno

true se la stringa è null, false altrimenti.

## Vedi anche

* Classe [String](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)