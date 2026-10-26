---
title: LastIndexOfAny()
second_title: Riferimento API Aspose.Slides per C++
description: Cerca uno qualsiasi dei caratteri passati in tutta la stringa in modo retroverso. Confronta l'ultimo carattere della stringa con tutti i caratteri in anyOf, poi confronta quello precedente e così via. Restituisce l'indice della prima corrispondenza trovata.
type: docs
weight: 664
url: /it/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const metodo

Cerca uno qualsiasi dei caratteri passati attraverso l'intera stringa in modo retroverso. Confronta l'ultimo carattere della stringa con tutti i caratteri in anyOf, poi confronta quello precedente e così via. Restituisce l'indice della prima corrispondenza trovata.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) di caratteri da cercare. L'ordine non è importante. |

### Valore di ritorno

[Index](../../index/) dell'ultimo carattere corrispondente o -1 se non trovato.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metodo

Cerca uno qualsiasi dei caratteri passati attraverso la sottostringa in modo retroverso. Confronta l'ultimo carattere della stringa con tutti i caratteri in anyOf, poi confronta quello precedente e così via. Restituisce l'indice della prima corrispondenza trovata.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) di caratteri da cercare. L'ordine non è importante. |
| startindex | **int32_t** | [Index](../../index/) da cui iniziare la ricerca. |

### Valore di ritorno

[Index](../../index/) dell'ultimo carattere corrispondente o -1 se non trovato.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metodo

Cerca uno qualsiasi dei caratteri passati attraverso la sottostringa in modo retroverso. Confronta l'ultimo carattere della stringa con tutti i caratteri in anyOf, poi confronta quello precedente e così via. Restituisce l'indice della prima corrispondenza trovata.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) di caratteri da cercare. L'ordine non è importante. |
| startindex | **int32_t** | [Index](../../index/) da cui iniziare la ricerca. |
| count | **int32_t** | Numero di caratteri da esaminare. |

### Valore di ritorno

[Index](../../index/) dell'ultimo carattere corrispondente o -1 se non trovato.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)