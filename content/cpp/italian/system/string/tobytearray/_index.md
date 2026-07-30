---
title: ToByteArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa o una sottostringa in un array di byte.
type: docs
weight: 508
url: /it/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const metodo


Converte la stringa o una sottostringa in un array di byte.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **int32_t** | Indice di inizio della sottostringa. |
| length | **int32_t** | Lunghezza della sottostringa. |
| LE | **bool** | Se vero, codifica i caratteri usando il little endian; altrimenti, usa il big endian. |

### Valore di ritorno

[Array](../../array/) contenente byte che rappresentano i caratteri della stringa.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)