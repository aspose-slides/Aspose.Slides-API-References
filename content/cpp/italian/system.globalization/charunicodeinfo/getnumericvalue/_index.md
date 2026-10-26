---
title: GetNumericValue()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore numerico associato al carattere specificato.
type: docs
weight: 27
url: /it/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) method


Restituisce il valore numerico associato al carattere specificato.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ch | char16_t | Carattere Unicode. |

### Valore di ritorno

Il valore numerico o -1 se il carattere specificato non è un carattere numerico.

## CharUnicodeInfo::GetNumericValue(const String\&, int) method


Restituisce il valore numerico associato al carattere all'indice specificato della stringa.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La stringa contenente il carattere Unicode. |
| index | int | L'indice del carattere Unicode. |

### Valore di ritorno

Il valore numerico o -1 se il carattere specificato non è un carattere numerico.

## Vedi anche

* Classe [CharUnicodeInfo](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Globalization](../../)
* Libreria [Aspose.Slides](../../../)