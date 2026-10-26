---
title: ToInt64()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в 64-битное целое значение.
type: docs
weight: 79
url: /ru/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) метод

Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в 64-битное целое значение.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинать брать байты для преобразования |

### Возвращаемое значение

64-битное целое значение, полученное в результате преобразования

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) метод

Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в 64-битное целое значение.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинать брать байты для преобразования |

### Возвращаемое значение

64-битное целое значение, полученное в результате преобразования

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [BitConverter](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)