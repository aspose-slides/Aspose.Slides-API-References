---
title: FromBase64CharArray()
second_title: Riferimento API Aspose.Slides per C++
description: Decodifica i dati codificati in base-64 rappresentati come un intervallo nell'array di caratteri Unicode.
type: docs
weight: 53
url: /it/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) metodo

Decodifica i dati codificati in base-64 rappresentati come un intervallo nell'array di caratteri Unicode.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | L'array che contiene i dati da decodificare |
| offset | int | La posizione nell'array di input in cui inizia l'intervallo da decodificare |
| length | int | La lunghezza dell'intervallo da decodificare |

### Valore di ritorno

Un array di byte contenente i dati decodificati

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)