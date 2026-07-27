---
title: UrlEncode()
second_title: Referência da API Aspose.Slides para C++
description: Codifica fragmento de URI.
type: docs
weight: 53
url: /pt/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) método


Codifica fragmento de URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmento de URI a ser codificado. |

### Valor de Retorno

Fragmento de URI codificado.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) método


Codifica fragmento de URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmento de URI a ser codificado. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificação a ser usada. |

### Valor de Retorno

Fragmento de URI codificado.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) método


Codifica fragmento de URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI a ser codificado. |

### Valor de Retorno

Fragmento de URI codificado.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Codifica fragmento de URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI a ser codificado. |
| offset | **int32_t** | Deslocamento no array de bytes fornecido. |
| count | **int32_t** | Número de bytes a serem lidos. |

### Valor de Retorno

Fragmento de URI codificado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [HttpUtility](../)
* Classe [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)