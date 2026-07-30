---
title: IndexOfAny()
second_title: Riferimento API di Aspose.Slides per C++
description: Ricerca in avanti del carattere.
type: docs
weight: 638
url: /it/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const metodo

Ricerca in avanti del carattere.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | char_t | Carattere da cercare. |
| startIndex | int | [Index](../../index/) per avviare la ricerca a. |

### Valore di ritorno

[Index](../../index/) della prima posizione del carattere a partire da startIndex o -1 se non trovata.

## String::IndexOfAny(const String\&, int) const metodo

Cerca quindi tutti i caratteri di str in questo. Se il primo carattere viene trovato, ne viene restituita la posizione, altrimenti cerca il secondo e così via.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) dei caratteri da cercare. L'ordine dei caratteri è importante. |
| startIndex | int | Posizione da cui avviare la ricerca. |

### Valore di ritorno

[Index](../../index/) del primo carattere trovato o -1 se non ne è stato trovato alcuno.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const metodo

Cerca uno qualsiasi dei caratteri forniti nell'intera stringa. Confronta il primo carattere della stringa con tutti i caratteri in anyOf, poi confronta il secondo e così via. Restituisce l'indice del primo che corrisponde a uno dei caratteri target.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) dei caratteri da cercare. L'ordine non è importante. |

### Valore di ritorno

[Index](../../index/) del primo carattere corrispondente o -1 se non trovato.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metodo

Cerca uno qualsiasi dei caratteri forniti in una sottostringa. Confronta il primo carattere della stringa con tutti i caratteri in anyOf, poi confronta il secondo e così via. Restituisce l'indice del primo che corrisponde a uno dei caratteri target.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) dei caratteri da cercare. L'ordine non è importante. |
| startindex | **int32_t** | [Index](../../index/) per avviare la ricerca da. |

### Valore di ritorno

[Index](../../index/) del primo carattere corrispondente o -1 se non trovato.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metodo

Cerca uno qualsiasi dei caratteri forniti in una sottostringa. Confronta il primo carattere della stringa con tutti i caratteri in anyOf, poi confronta il secondo e così via. Restituisce l'indice del primo che corrisponde a uno dei caratteri target.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) dei caratteri da cercare. L'ordine non è importante. |
| startindex | **int32_t** | [Index](../../index/) per avviare la ricerca da. |
| count | **int32_t** | Numero di caratteri da esaminare. |

### Valore di ritorno

[Index](../../index/) del primo carattere corrispondente o -1 se non trovato.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)