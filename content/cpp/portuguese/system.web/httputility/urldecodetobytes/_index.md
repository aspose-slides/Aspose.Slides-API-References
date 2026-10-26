---
title: UrlDecodeToBytes()
second_title: Referência da API Aspose.Slides para C++
description: Decodifica o fragmento URI a partir de um array de bytes.
type: docs
weight: 14
url: /pt/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) método


Decodifica o fragmento URI a partir de um array de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento URI codificado. |

### Valor de Retorno

Fragmento URI decodificado.

## HttpUtility::UrlDecodeToBytes(const String\&) método


Decodifica o fragmento URI a partir de uma string de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragmento URI codificado. |

### Valor de Retorno

Fragmento URI decodificado.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) método


Decodifica o fragmento URI a partir de uma string.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragmento URI codificado. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificação a ser usada. |

### Valor de Retorno

Fragmento URI decodificado.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Decodifica o fragmento URI a partir de um array de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento URI codificado. |
| offset | **int32_t** | Deslocamento no array de bytes fornecido. |
| count | **int32_t** | Número de bytes a ler. |

### Valor de Retorno

Fragmento URI decodificado.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpUtility](../)
* Classe [String](../../../system/string/)
* Classe [Encoding](../../../system.text/encoding/)
* Espaço de nomes [System::Web](../../)
* Library [Aspose.Slides](../../../)