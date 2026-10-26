---
title: ToBase64CharArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Base-64 codifica un intervallo di elementi nell'array di byte specificato e memorizza i dati codificati come un array di caratteri Unicode.
type: docs
weight: 27
url: /it/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) metodo


Base-64 codifica un intervallo di elementi nell'array di byte specificato e memorizza i dati codificati come un array di caratteri Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | L'array di byte contenente l'intervallo di elementi da codificare |
| offset_in | int | Un indice di un elemento nell'array di input in cui inizia l'intervallo da codificare |
| length | int | La lunghezza dell'intervallo di elementi da codificare |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Un riferimento costante all'array di output in cui inserire i dati risultanti |
| offset_out | int | Un indice nell'array di output in cui iniziare a inserire i dati risultanti |
| insert_line_breaks | **bool** | Specifica se i caratteri di interruzione di riga devono essere inseriti nell'array di output dopo ogni 76 caratteri base-64 |

### Valore di ritorno

Il numero di caratteri scritti nell'array di output

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) metodo


Base-64 codifica un intervallo di elementi nell'array di byte specificato e memorizza i dati codificati come un array di caratteri Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | L'array di byte contenente l'intervallo di elementi da codificare |
| offset_in | int | Un indice di un elemento nell'array di input in cui inizia l'intervallo da codificare |
| length | int | La lunghezza dell'intervallo di elementi da codificare |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Un riferimento costante all'array di output in cui inserire i dati risultanti |
| offset_out | int | Un indice nell'array di output in cui iniziare a inserire i dati risultanti |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Specifica le opzioni di formattazione dei dati codificati in base-64 |

### Valore di ritorno

Il numero di caratteri scritti nell'array di output

## Vedi anche

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)