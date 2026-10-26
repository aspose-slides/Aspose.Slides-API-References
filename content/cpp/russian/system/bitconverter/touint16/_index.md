---
title: ToUInt16()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует два байта из указанного массива, начиная с указанного индекса, в беззнаковое 16-разрядное целое значение.
type: docs
weight: 92
url: /ru/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) метод

Преобразует два байта из указанного массива, начиная с указанного индекса, в беззнаковое 16-разрядное целое значение.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) которая содержит байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начать брать байты для преобразования |

### Возвращаемое значение

Беззнаковое 16-разрядное целое значение, полученное в результате преобразования

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) метод

Преобразует два байта из указанного массива, начинающегося с указанного индекса, в беззнаковое 16-разрядное целое значение.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, которая содержит байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начать брать байты для преобразования |

### Возвращаемое значение

Беззнаковое 16-разрядное целое значение, полученное в результате преобразования

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [BitConverter](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)