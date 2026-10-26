---
title: ToBase64String()
second_title: Riferimento API di Aspose.Slides per C++
description: Base-64 codifica gli elementi nell'array di byte specificato e restituisce i dati codificati come stringa.
type: docs
weight: 40
url: /it/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) metodo


Codifica in Base-64 gli elementi nell'array di byte specificato e restituisce i dati codificati come stringa.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | L'array di byte da codificare |
| insert_line_breaks | **bool** | Specifica se i caratteri di interruzione di riga devono essere inseriti nella stringa di output dopo ogni 76 caratteri Base-64 |

### Valore di ritorno

La stringa contenente la rappresentazione codificata in Base-64 dell'array di input

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) metodo


Codifica in Base-64 un intervallo di elementi nell'array di byte specificato e restituisce i dati codificati come stringa.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | L'array di byte contenente l'intervallo di elementi da codificare |
| offset_in | int | Un indice di un elemento nell'array di input da cui inizia l'intervallo da codificare |
| length | int | La lunghezza dell'intervallo di elementi da codificare |
| insert_line_breaks | **bool** | Specifica se i caratteri di interruzione di riga devono essere inseriti nella stringa di output dopo ogni 76 caratteri Base-64 |

### Valore di ritorno

La stringa contenente la rappresentazione codificata in Base-64 dell'intervallo di elementi dell'array di input

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) metodo


Codifica in Base-64 gli elementi nell'array di byte specificato e restituisce i dati codificati come stringa.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | L'array di byte da codificare |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Specifica le opzioni di formattazione dei dati codificati in Base-64 |

### Valore di ritorno

La stringa contenente la rappresentazione codificata in Base-64 dell'array di input

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) metodo


Codifica in Base-64 un intervallo di elementi nell'array di byte specificato e restituisce i dati codificati come stringa.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | L'array di byte contenente l'intervallo di elementi da codificare |
| offset_in | int | Un indice di un elemento nell'array di input da cui inizia l'intervallo da codificare |
| length | int | La lunghezza dell'intervallo di elementi da codificare |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Specifica le opzioni di formattazione dei dati codificati in Base-64 |

### Valore di ritorno

La stringa contenente la rappresentazione codificata in Base-64 dell'intervallo di elementi dell'array di input

## Vedi anche

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../../string/)
* Struttura [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)