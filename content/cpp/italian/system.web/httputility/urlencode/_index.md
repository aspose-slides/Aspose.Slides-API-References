---
title: UrlEncode()
second_title: Riferimento API Aspose.Slides per C++
description: Codifica il frammento URI.
type: docs
weight: 53
url: /it/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) method

Codifica il frammento URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../../../system/string/) | Frammento URI da codificare. |

### Valore restituito

Frammento URI codificato.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) method

Codifica il frammento URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../../../system/string/) | Frammento URI da codificare. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codifica da utilizzare. |

### Valore restituito

Frammento URI codificato.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) method

Codifica il frammento URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Frammento URI da codificare. |

### Valore restituito

Frammento URI codificato.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Codifica il frammento URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)