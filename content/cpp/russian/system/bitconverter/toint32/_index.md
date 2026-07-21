---
title: ToInt32()
second_title: Aspose.Slides для C++: справка API
description: Преобразует четыре байта из указанного массива, начиная с указанного индекса, в 32-разрядное целочисленное значение.
type: docs
weight: 66
url: /ru/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) method

Преобразует четыре байта из указанного массива, начиная с указанного индекса, в 32-разрядное целочисленное значение.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинается чтение байтов для преобразования |

### Возвращаемое значение

32-разрядное целочисленное значение, полученное в результате преобразования

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method

Преобразует четыре байта из указанного массива, начиная с указанного индекса, в 32-разрядное целочисленное значение.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинается чтение байтов для преобразования |

### Возвращаемое значение

32-разрядное целочисленное значение, полученное в результате преобразования

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [BitConverter](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)