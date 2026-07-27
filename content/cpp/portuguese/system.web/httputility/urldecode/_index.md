---
title: UrlDecode()
second_title: Referência da API Aspose.Slides para C++
description: Decodifica fragmento de URI a partir de string.
type: docs
weight: 1
url: /pt/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) método


Decodifica fragmento de URI a partir de string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmento de URI codificado. |

### Valor de Retorno

Fragmento de URI decodificado.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) método


Decodifica fragmento de URI a partir de string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmento de URI codificado. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Codificação a ser usada. |

### Valor de Retorno

Fragmento de URI decodificado.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) método


Decodifica fragmento de URI a partir de array de bytes.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI codificado. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificação a ser usada. |

### Valor de Retorno

Fragmento de URI decodificado.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) método


Decodifica fragmento de URI a partir de array de bytes.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI codificado. |
| offset | **int32_t** | Deslocamento no array de bytes fornecido. |
| count | **int32_t** | Número de bytes a ler. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificação a ser usada. |

### Valor de Retorno

Fragmento de URI decodificado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [HttpUtility](../)
* Classe [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)