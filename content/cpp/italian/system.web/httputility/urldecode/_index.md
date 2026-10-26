---
title: UrlDecode()
second_title: Riferimento API di Aspose.Slides per C++
description: Decodifica il frammento URI da una stringa.
type: docs
weight: 1
url: /it/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) metodo

Decodifica il frammento URI da una stringa.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../../../system/string/) | Frammento URI codificato. |

### Valore restituito

Frammento URI decodificato.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) metodo

Decodifica il frammento URI da una stringa.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../../../system/string/) | Frammento URI codificato. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Codifica da usare. |

### Valore restituito

Frammento URI decodificato.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) metodo

Decodifica il frammento URI da un array di byte.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Frammento URI codificato. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codifica da usare. |

### Valore restituito

Frammento URI decodificato.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) metodo

Decodifica il frammento URI da un array di byte.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Frammento URI codificato. |
| offset | **int32_t** | Offset nell'array di byte fornito. |
| count | **int32_t** | Numero di byte da leggere. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codifica da usare. |

### Valore restituito

Frammento URI decodificato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [HttpUtility](../)
* Classe [Encoding](../../../system.text/encoding/)
* Spazio dei nomi [System::Web](../../)
* Library [Aspose.Slides](../../../)