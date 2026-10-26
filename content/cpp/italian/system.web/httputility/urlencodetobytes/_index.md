---
title: UrlEncodeToBytes()
second_title: Riferimento API di Aspose.Slides per C++
description: Codifica il frammento URI.
type: docs
weight: 66
url: /it/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) metodo


Codifica il frammento URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Frammento URI da codificare. |

### Valore restituito

Frammento URI codificato.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metodo


Codifica il frammento URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Frammento URI da codificare. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codifica da usare. |

### Valore restituito

Frammento URI codificato.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metodo


Codifica il frammento URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Frammento URI da codificare. |

### Valore restituito

Frammento URI codificato.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo


Codifica il frammento URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Frammento URI da codificare. |
| offset | **int32_t** | Offset nell'array di byte fornito. |
| count | **int32_t** | Numero di byte da leggere. |

### Valore restituito

Frammento URI codificato.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [HttpUtility](../)
* Classe [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)