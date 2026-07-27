---
title: UrlEncode()
second_title: Referencia de la API de Aspose.Slides para C++
description: Codifica fragmento de URI.
type: docs
weight: 53
url: /es/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) método

Codifica fragmento de URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmento de URI a codificar. |

### Valor devuelto

Fragmento de URI codificado.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) método

Codifica fragmento de URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmento de URI a codificar. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificación a usar. |

### Valor devuelto

Fragmento de URI codificado.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) método

Codifica fragmento de URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI a codificar. |

### Valor devuelto

Fragmento de URI codificado.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Codifica fragmento de URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI a codificar. |
| offset | **int32_t** | Desplazamiento en la matriz de bytes dada. |
| count | **int32_t** | Número de bytes a leer. |

### Valor devuelto

Fragmento de URI codificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [HttpUtility](../)
* Clase [Encoding](../../../system.text/encoding/)
* Espacio de nombres [System::Web](../../)
* Biblioteca [Aspose.Slides](../../../)