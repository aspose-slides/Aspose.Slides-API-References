---
title: UrlDecodeToBytes()
second_title: Riferimento API Aspose.Slides per C++
description: Decodifica il frammento URI da un array di byte.
type: docs
weight: 14
url: /it/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metodo

Decodifica il frammento URI da un array di byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Frammento URI codificato. |

### Valore di ritorno

Frammento URI decodificato.

## HttpUtility::UrlDecodeToBytes(const String\&) metodo

Decodifica il frammento URI da una stringa di byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Frammento URI codificato. |

### Valore di ritorno

Frammento URI decodificato.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metodo

Decodifica il frammento URI da una stringa.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Frammento URI codificato. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codifica da utilizzare. |

### Valore di ritorno

Frammento URI decodificato.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Decodifica il frammento URI da un array di byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Frammento URI codificato. |
| offset | **int32_t** | Offset nell'array di byte fornito. |
| count | **int32_t** | Numero di byte da leggere. |

### Valore di ritorno

Frammento URI decodificato.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpUtility](../)
* Class [String](../../../system/string/)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)