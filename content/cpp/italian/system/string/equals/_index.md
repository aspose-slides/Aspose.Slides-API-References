---
title: Equals()
second_title: Riferimento API Aspose.Slides per C++
description: Confronto di uguaglianza di stringhe. Sono supportate diverse modalità fornite dall'enumerazione StringComparison.
type: docs
weight: 391
url: /it/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const metodo

[String](../) confronto di uguaglianza. Sono supportate diverse modalità fornite dall'enumerazione StringComparison.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) da confrontare con quello corrente. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità (vedi [System::StringComparison](../../stringcomparison/) per i dettagli). |

### Valore di ritorno

true se le stringhe corrispondono usando il tipo di confronto selezionato, false altrimenti.

## String::Equals(const String\&) const metodo

[String](../) confronto di uguaglianza. Usa la modalità di confronto [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) da confrontare con quello corrente. |

### Valore di ritorno

true se le stringhe corrispondono, false altrimenti.

## String::Equals(const String\&, const String\&) metodo

Confronta due stringhe usando la modalità di confronto Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |

### Valore di ritorno

true se le stringhe corrispondono, false.

## String::Equals(const String\&, const String\&, System::StringComparison) metodo

Confronta due stringhe.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Prima stringa da confrontare. |
| strB | const [String](../)\& | Seconda stringa da confrontare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | modalità [Comparison](../../comparison/). |

### Valore di ritorno

true se le stringhe corrispondono, false.

## Vedi anche

* Enum [StringComparison](../../stringcomparison/)
* Classe [String](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)