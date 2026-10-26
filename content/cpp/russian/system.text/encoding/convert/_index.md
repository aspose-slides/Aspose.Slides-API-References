---
title: Convert()
second_title: Aspose.Slides для C++ справка API
description: Преобразует байты между двумя кодировками.
type: docs
weight: 378
url: /ru/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) method


Преобразует байты между двумя кодировками.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Исходная кодировка. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Целевая кодировка. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Байты для преобразования. |

### Возвращаемое значение

Преобразованные байты.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) method


Преобразует байты между двумя кодировками.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Исходная кодировка. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Целевая кодировка. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Байты для преобразования. |
| index | int | Начало среза. |
| count | int | Размер среза. |

### Возвращаемое значение

Преобразованные байты.

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Тип-определение [EncodingPtr](../../../system/encodingptr/)
* Класс [Encoding](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)