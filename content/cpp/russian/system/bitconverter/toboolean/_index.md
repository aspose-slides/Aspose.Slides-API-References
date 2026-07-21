---
title: ToBoolean()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует один байт из указанного массива, начиная с указанного индекса, в логическое значение.
type: docs
weight: 27
url: /ru/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) метод

Преобразует один байт из указанного массива, начиная с указанного индекса, в логическое значение.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинается взятие байтов для преобразования |

### Возвращаемое значение

[Boolean](../../boolean/) значение, полученное в результате преобразования

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) метод

Преобразует один байт из указанного массива, начиная с указанного индекса, в логическое значение.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинается взятие байтов для преобразования |

### Возвращаемое значение

[Boolean](../../boolean/) значение, полученное в результате преобразования

## Смотри также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [BitConverter](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)