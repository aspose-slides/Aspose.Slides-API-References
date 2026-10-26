---
title: FindIndex()
second_title: Aspose.Slides per C++ Riferimento API
description: Cerca un elemento che soddisfa un predicato specifico.
type: docs
weight: 404
url: /it/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) metodo

Cerca un elemento che soddisfa un predicato specifico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicato per verificare gli elementi. |

### Valore di ritorno

[Index](../../../system/index/) dell'elemento corrispondente o -1 se non trovato.

## List::FindIndex(int, System::Predicate\<T\>) metodo

Cerca un elemento che soddisfa un predicato specifico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) da cui iniziare la ricerca. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicato per verificare gli elementi. |

### Valore di ritorno

[Index](../../../system/index/) dell'elemento corrispondente o -1 se non trovato.

## List::FindIndex(int, int, System::Predicate\<T\>) metodo

Cerca un elemento che soddisfa un predicato specifico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) da cui iniziare la ricerca. |
| count | int | Numero di elementi da esaminare. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicato per verificare gli elementi. |

### Valore di ritorno

[Index](../../../system/index/) dell'elemento corrispondente o -1 se non trovato.

## Vedi anche

* Typedef [Predicate](../../../system/predicate/)
* Classe [List](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)