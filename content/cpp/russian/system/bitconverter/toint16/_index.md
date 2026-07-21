---
title: ToInt16()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует два байта из указанного массива, начиная с указанного индекса, в 16-битное целое значение.
type: docs
weight: 53
url: /ru/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) метод

Преобразует два байта из указанного массива, начиная с указанного индекса, в 16-битное целое значение.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинать брать байты для преобразования |

### Возвращаемое значение

16-битное целое значение, полученное в результате преобразования

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) метод

Преобразует два байта из указанного массива, начиная с указанного индекса, в 16-битное целое значение.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинать брать байты для преобразования |

### Возвращаемое значение

16-битное целое значение, полученное в результате преобразования

## См. также

* Тип [ArrayPtr](../../arrayptr/)
* Класс [BitConverter](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)