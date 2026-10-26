---
title: IsHighSurrogate()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se il carattere all'indice specificato nella stringa specificata è un'unità di codice surrogate alto UTF-16.
type: docs
weight: 40
url: /it/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) metodo


Determina se il carattere all'indice specificato nella stringa specificata è un'unità di codice surrogate alto UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | Una stringa |
| index | int | L'indice nella stringa specificata del carattere da testare |

### Valore di ritorno

True se il carattere all'indice specificato è un'unità di codice surrogate alto UTF-16, altrimenti - false

## Char::IsHighSurrogate(const char_t *, int) metodo


Determina se il carattere all'indice specificato nel buffer di caratteri specificato è un surrogate alto.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const char_t * | Puntatore all'inizio del buffer di caratteri |
| idx | int | Un indice basato su zero nel buffer specificato del carattere da testare |

### Valore di ritorno

True se il carattere all'indice specificato è un surrogate alto, altrimenti - false

## Char::IsHighSurrogate(char_t) metodo


Determina se il carattere specificato è un surrogate alto.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | char_t | Il carattere da testare |

### Valore di ritorno

True se il carattere specificato è un surrogate alto, altrimenti - false

## Vedi anche

* Classe [String](../../string/)
* Classe [Char](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)