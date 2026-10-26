---
title: CompareOrdinal()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta due stringhe usando la modalità ordinale.
type: docs
weight: 833
url: /it/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) metodo

Confronta due stringhe usando la modalità ordinale.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |

### Valore di ritorno

Valore negativo se la prima sottostringa è inferiore alla seconda, zero se corrispondono, valore positivo altrimenti.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) metodo

Confronta due stringhe usando la modalità ordinale.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| indexA | int | Inizio della prima sottostringa. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |
| indexB | int | Inizio della seconda sottostringa. |
| length | int | Numero di caratteri da confrontare. |

### Valore di ritorno

Valore negativo se la prima sottostringa è inferiore alla seconda, zero se corrispondono, valore positivo altrimenti.

## Vedi anche

* Classe [String](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)