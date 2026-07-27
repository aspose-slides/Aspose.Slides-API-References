---
title: UrlEncodeToBytes()
second_title: Referencia de API de Aspose.Slides para C++
description: Codifica fragmento de URI.
type: docs
weight: 66
url: /es/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) método


Codifica fragmento de URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragmento de URI a codificar. |

### Valor devuelto

Fragmento de URI codificado.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) método


Codifica fragmento de URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragmento de URI a codificar. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificación a usar. |

### Valor devuelto

Fragmento de URI codificado.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) método


Codifica fragmento de URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI a codificar. |

### Valor devuelto

Fragmento de URI codificado.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Codifica fragmento de URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI a codificar. |
| offset | **int32_t** | Desplazamiento en el arreglo de bytes dado. |
| count | **int32_t** | Número de bytes a leer. |

### Valor devuelto

Fragmento de URI codificado.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)