---
title: UrlDecodeToBytes()
second_title: Referencia de API de Aspose.Slides para C++
description: Decodifica un fragmento de URI a partir de una matriz de bytes.
type: docs
weight: 14
url: /es/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) método

Decodifica un fragmento de URI a partir de una matriz de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI codificado. |

### Return Value

Fragmento de URI decodificado.

## HttpUtility::UrlDecodeToBytes(const String\&) método

Decodifica un fragmento de URI a partir de una cadena de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragmento de URI codificado. |

### Return Value

Fragmento de URI decodificado.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) método

Decodifica un fragmento de URI a partir de una cadena.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragmento de URI codificado. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Codificación a usar. |

### Return Value

Fragmento de URI decodificado.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Decodifica un fragmento de URI a partir de una matriz de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmento de URI codificado. |
| offset | **int32_t** | Desplazamiento en la matriz de bytes dada. |
| count | **int32_t** | Número de bytes a leer. |

### Return Value

Fragmento de URI decodificado.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpUtility](../)
* Class [String](../../../system/string/)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)