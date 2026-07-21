---
title: GetCharCount()
second_title: Aspose.Slides для C++ справочник API
description: Получает количество символов, необходимых для декодирования буфера байтов.
type: docs
weight: 261
url: /ru/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) метод

Получает количество символов, необходимое для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| index | int | Начало среза. |
| count | int | Размер среза. |

### Возвращаемое значение

Количество символов.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) метод

Получает количество символов, необходимое для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |

### Возвращаемое значение

Количество символов.

## Encoding::GetCharCount(const uint8_t *, int) метод

Получает количество символов, необходимое для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| count | int | Количество байтов. |

### Возвращаемое значение

Количество символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Encoding](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)