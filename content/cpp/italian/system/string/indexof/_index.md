---
title: IndexOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Ricerca in avanti di sottostringa.
type: docs
weight: 625
url: /it/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const metodo

Ricerca in avanti di sottostringa.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | Sottostringa da cercare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità. |

### Valore di ritorno

[Index](../../index/) del primo sottostringa trovato o -1 se non trovato. Per stringa di ricerca vuota, restituisce sempre 0.

## String::IndexOf(char_t, int) const metodo

Ricerca in avanti di carattere.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | char_t | Carattere da cercare. |
| startIndex | int | [Index](../../index/) per avviare la ricerca a. |

### Valore di ritorno

[Index](../../index/) della prima posizione del carattere a partire da startIndex o -1 se non trovato.

## String::IndexOf(char_t, int, int) const metodo

Ricerca in avanti di carattere in sottostringa.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | char_t | Carattere da cercare. |
| startIndex | int | [Index](../../index/) per avviare la ricerca a. |
| count | int | Numero di caratteri da esaminare. |

### Valore di ritorno

[Index](../../index/) della prima posizione del carattere a partire da startIndex o -1 se non trovato.

## String::IndexOf(const String\&, int) const metodo

Ricerca in avanti di sottostringa.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | Sottostringa da cercare. |
| startIndex | int | Posizione nella stringa di origine per avviare la ricerca. |

### Valore di ritorno

[Index](../../index/) del primo sottostringa trovato o -1 se non trovato. Per stringa di ricerca vuota, restituisce sempre startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const metodo

Ricerca in avanti di sottostringa.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | Sottostringa da cercare. |
| startIndex | int | Posizione nella stringa di origine per avviare la ricerca. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità. |

### Valore di ritorno

[Index](../../index/) del primo sottostringa trovato o -1 se non trovato. Per stringa di ricerca vuota, restituisce sempre startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const metodo

Ricerca in avanti di sottostringa.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../)\& | Sottostringa da cercare. |
| startIndex | int | Posizione nella stringa di origine per avviare la ricerca. |
| count | int | numero di caratteri da esaminare. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità. |

### Valore di ritorno

[Index](../../index/) del primo sottostringa trovato o -1 se non trovato. Per stringa di ricerca vuota, restituisce sempre startIndex.

## String::IndexOf(const String\&, int, int) const metodo

Ricerca in avanti di sottostringa.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | Sottostringa da cercare. |
| startIndex | int | Posizione nella stringa di origine per avviare la ricerca. |
| count | int | numero di caratteri da esaminare. |

### Valore di ritorno

[Index](../../index/) del primo sottostringa trovato o -1 se non trovato. Per stringa di ricerca vuota, restituisce sempre startIndex.

## Vedi anche

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)