---
title: GetEncoding()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene la codificación por nombre.
type: docs
weight: 508
url: /es/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) método

Obtiene la codificación por nombre.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nombre. |

### Valor de retorno

[Encoding](../) del nombre especificado.

## Encoding::GetEncoding(int) método

Obtiene la codificación por página de códigos.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codepage | int | número de página de códigos. |

### Valor de retorno

[Encoding](../) de la página de códigos especificada.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) método

Obtiene la codificación por página de códigos.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codepage | int | número de página de códigos. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Valor de reserva a usar para la codificación. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Valor de reserva a usar para la decodificación. |

### Valor de retorno

[Encoding](../) de la página de códigos especificada.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) método

Obtiene la codificación por nombre.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nombre. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Valor de reserva a usar para la codificación. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Valor de reserva a usar para la decodificación. |

### Valor de retorno

[Encoding](../) del nombre especificado.

## Ver también

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)