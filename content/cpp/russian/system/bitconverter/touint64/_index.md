---
title: ToUInt64()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в беззнаковое 64-битное целое значение.
type: docs
weight: 118
url: /ru/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) метод

Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в беззнаковое 64-битное целое значение.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) который содержит байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинается взятие байтов для преобразования |

### Возвращаемое значение

Беззнаковое 64-битное целое значение, полученное в результате преобразования

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) метод

Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в беззнаковое 64-битное целое значение.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView который содержит байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинается взятие байтов для преобразования |

### Возвращаемое значение

Беззнаковое 64-битное целое значение, полученное в результате преобразования

## См. также

* Тип [ArrayPtr](../../arrayptr/)
* Класс [BitConverter](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)