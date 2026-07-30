---
title: LastIndexOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Ricerca retrospettiva di sottostringhe.
type: docs
weight: 651
url: /it/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const method


Ricerca retrospettiva della sottostringa.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | Sottostringa da cercare. |
| startIndex | int | Posizione nella stringa di origine da cui avviare la ricerca. |

### Valore di ritorno

[Index](../../index/) dell'ultima sottostringa trovata o -1 se non trovata. Per stringa di ricerca vuota, restituisce sempre la lunghezza della stringa.

## String::LastIndexOf(const String\&, System::StringComparison) const method


Ricerca retrospettiva della sottostringa.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | Sottostringa da cercare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità. |

### Valore di ritorno

[Index](../../index/) dell'ultima sottostringa trovata o -1 se non trovata. Per stringa di ricerca vuota, restituisce sempre la lunghezza della stringa.

## String::LastIndexOf(const String\&, int, System::StringComparison) const method


Ricerca retrospettiva della sottostringa.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | Sottostringa da cercare. |
| startIndex | int | Posizione nella stringa di origine da cui avviare la ricerca. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità. |

### Valore di ritorno

[Index](../../index/) dell'ultima sottostringa trovata o -1 se non trovata. Per stringa di ricerca vuota, restituisce sempre la lunghezza della stringa.

## String::LastIndexOf(const String\&, int, int, StringComparison) const method


Ricerca retrospettiva della sottostringa.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../)\& | Sottostringa da cercare. |
| startIndex | int | Posizione nella stringa di origine da cui avviare la ricerca. |
| count | int | Numero di caratteri da esaminare. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modalità. |

### Valore di ritorno

[Index](../../index/) dell'ultima sottostringa trovata o -1 se non trovata. Per stringa di ricerca vuota, restituisce sempre startIndex+count.

## String::LastIndexOf(char_t) const method


Ricerca retrospettiva del carattere.

```cpp
int System::String::LastIndexOf(char_t value) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Carattere da cercare. |

### Valore di ritorno

[Index](../../index/) dell'ultima posizione del carattere o -1 se non trovata.

## String::LastIndexOf(char_t, int32_t) const method


Ricerca retrospettiva del carattere.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Carattere da cercare. |
| startIndex | **int32_t** | [Index](../../index/) per avviare la ricerca a. |

### Valore di ritorno

[Index](../../index/) dell'ultima posizione del carattere a partire da startIndex o -1 se non trovata.

## String::LastIndexOf(char_t, int32_t, int32_t) const method


Ricerca retrospettiva del carattere.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Carattere da cercare. |
| startIndex | **int32_t** | [Index](../../index/) per avviare la ricerca a. |
| count | **int32_t** | Numero di caratteri da esaminare |

### Valore di ritorno

[Index](../../index/) dell'ultima posizione del carattere a partire da startIndex o -1 se non trovata.

## Vedi anche

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)