---
title: ToChar()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует два байта из указанного массива, начиная с указанного индекса, в значение char_t.
type: docs
weight: 40
url: /ru/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) метод

Преобразует два байта из указанного массива, начиная с указанного индекса, в значение char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинается взятие байтов для преобразования |

### Возвращаемое значение

char_t значение, полученное в результате преобразования

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) метод

Преобразует два байта из указанного массива, начиная с указанного индекса, в значение char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинается взятие байтов для преобразования |

### Возвращаемое значение

char_t значение, полученное в результате преобразования

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [BitConverter](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)