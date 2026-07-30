---
title: operator>>()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene una stringa dal flusso di input utilizzando la codifica UTF-8.
type: docs
weight: 3004
url: /it/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) funzione

Ottiene una stringa dal flusso di input utilizzando la codifica UTF-8.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in | std::istream\& | Un oggetto flusso di input (instanziazione di **basic_ostream** con **char**). |
| str | [String](../string/)\& | Una stringa da leggere dal flusso di input. |

### Valore di ritorno

Un flusso di input dal quale è stata estratta la stringa.

## System::operator>>(std::wistream\&, String\&) funzione

Ottiene una stringa dal flusso di input.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in | std::wistream\& | Un oggetto flusso di input (instanziazione di **basic_ostream** con ****wchar_t****). |
| str | [String](../string/)\& | Una stringa da leggere dal flusso di input. |

### Valore di ritorno

Un flusso di input dal quale è stata estratta la stringa.

## Vedi anche

* Classe [String](../string/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)