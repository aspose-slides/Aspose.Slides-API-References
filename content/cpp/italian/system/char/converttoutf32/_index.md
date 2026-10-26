---
title: ConvertToUtf32()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la coppia surrogata UTF-16 specificata in unità di codice UTF-32.
type: docs
weight: 287
url: /it/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) metodo


Converte la coppia surrogata UTF-16 specificata in unità di codice UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | Il surrogato alto della coppia surrogata UTF-16 da convertire |
| lowSurrogate | char_t | Il surrogato basso della coppia surrogata UTF-16 da convertire |

### Valore restituito

Un'unità di codice UTF-32 risultante dalla conversione

## Char::ConvertToUtf32(const String\&, int) metodo


Converte il valore di un carattere codificato in UTF-16 o di una coppia surrogata in una posizione specificata all'interno di una stringa in unità di codice UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Una stringa che contiene un carattere o una coppia surrogata |
| index | int | La posizione dell'indice del carattere o della coppia surrogata nella stringa specificata |

### Valore restituito

Un'unità di codice UTF-32 risultante dalla conversione

## Vedi anche

* Classe [Char](../)
* Classe [String](../../string/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)