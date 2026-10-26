---
title: UrlDecode()
second_title: Referencia de API de Aspose.Slides para C++
description: Decodifica el fragmento URI a partir de una cadena.
type: docs
weight: 1
url: /es/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) método

Decodifica el fragmento URI a partir de una cadena.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmento URI codificado. |

### Valor devuelto

Fragmento URI decodificado.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) método

Decodifica el fragmento URI a partir de una cadena.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmento URI codificado. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Codificación a usar. |

### Valor devuelto

Fragmento URI decodificado.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) método

Decodifica el fragmento URI a partir de una matriz de bytes.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento URI codificado. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificación a usar. |

### Valor devuelto

Fragmento URI decodificado.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) método

Decodifica el fragmento URI a partir de una matriz de bytes.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento URI codificado. |
| offset | **int32_t** | Desplazamiento en la matriz de bytes dada. |
| count | **int32_t** | Número de bytes a leer. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificación a usar. |

### Valor devuelto

Fragmento URI decodificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [HttpUtility](../)
* Clase [Encoding](../../../system.text/encoding/)
* Espacio de nombres [System::Web](../../)
* Library [Aspose.Slides](../../../)