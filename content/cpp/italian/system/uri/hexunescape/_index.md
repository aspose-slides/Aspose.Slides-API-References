---
title: HexUnescape()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la rappresentazione esadecimale specificata di un carattere in un carattere.
type: docs
weight: 443
url: /it/system/uri/hexunescape/
---
## Uri::HexUnescape(const String&, int32_t&) metodo

Converte la rappresentazione esadecimale specificata di un carattere in un carattere.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Una stringa contenente la rappresentazione esadecimale di un carattere |
| index | **int32_t**\& | La posizione in **pattern** dove inizia la rappresentazione esadecimale di un carattere |

### Valore di ritorno

Il carattere rappresentato dalla codifica esadecimale nella posizione **index**. Se il carattere in **index** non è codificato in esadecimale, viene restituito il carattere in **index**. Il valore di **index** viene incrementato per puntare al carattere successivo a quello restituito.

## Vedi anche

* Classe [String](../../string/)
* Classe [Uri](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)