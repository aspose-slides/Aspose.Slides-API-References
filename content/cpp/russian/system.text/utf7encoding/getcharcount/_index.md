---
title: GetCharCount()
second_title: Aspose.Slides для C++ API Reference
description: Получить количество символов, необходимых для декодирования буфера байтов.
type: docs
weight: 79
url: /ru/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) метод


Получить количество символов, необходимое для декодирования буфера байтов.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| index | int | Начало среза. |
| count | int | Размер среза. |

### Возвращаемое значение

Количество символов.

## UTF7Encoding::GetCharCount(const uint8_t *, int) метод


Получить количество символов, необходимое для декодирования буфера байтов.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| count | int | Количество байт. |

### Возвращаемое значение

Количество символов.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) метод


Получить количество символов, необходимое для декодирования буфера байтов.

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

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) метод


Получить количество символов, необходимое для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |

### Возвращаемое значение

Количество символов.

## UTF7Encoding::GetCharCount(const uint8_t *, int) метод


Получить количество символов, необходимое для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| count | int | Количество байт. |

### Возвращаемое значение

Количество символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [UTF7Encoding](../)
* Пространство имён [System::Text](../../)
* Library [Aspose.Slides](../../../)