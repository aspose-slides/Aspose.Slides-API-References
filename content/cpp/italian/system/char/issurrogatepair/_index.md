---
title: IsSurrogatePair()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se i due caratteri specificati costituiscono una coppia surrogate UTF-16.
type: docs
weight: 27
url: /it/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) metodo


Determina se i due caratteri specificati costituiscono una coppia surrogate UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| highSurrogate | char_t | Un carattere che viene testato per verificare se è un surrogato alto |
| lowSurrogate | char_t | Un carattere che viene testato per verificare se è un surrogato basso |

### Valore di ritorno

True se i caratteri specificati formano una coppia di surrogate, altrimenti - false

## Char::IsSurrogatePair(const String\&, int) metodo


Determina se due caratteri consecutivi nel buffer di caratteri specificato costituiscono una coppia surrogate.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../string/)\& | Una stringa |
| index | int | Un indice a base zero nel buffer specificato a partire del quale inizia la sequenza di caratteri da testare |

### Valore di ritorno

True se i caratteri specificati costituiscono una coppia di surrogate, altrimenti - false

## Vedi anche

* Classe [Char](../)
* Classe [String](../../string/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)