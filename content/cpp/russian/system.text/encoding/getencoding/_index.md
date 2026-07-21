---
title: GetEncoding()
second_title: Aspose.Slides для C++ справочник API
description: Получает кодировку по имени.
type: docs
weight: 508
url: /ru/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) метод

Получает кодировку по имени.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |

### Возвращаемое значение

[Encoding](../) of specified name.

## Encoding::GetEncoding(int) метод

Получает кодировку по кодовой странице.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| codepage | int | Codepage number. |

### Возвращаемое значение

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) метод

Получает кодировку по кодовой странице.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| codepage | int | Codepage number. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### Возвращаемое значение

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) метод

Получает кодировку по имени.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### Возвращаемое значение

[Encoding](../) of specified name.

## См. также

* Типовое определение [EncodingPtr](../../../system/encodingptr/)
* Типовое определение [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Типовое определение [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Класс [String](../../../system/string/)
* Класс [Encoding](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)