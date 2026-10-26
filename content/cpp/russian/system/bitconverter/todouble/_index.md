---
title: ToDouble()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в значение с двойной точностью.
type: docs
weight: 144
url: /ru/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) метод


Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в значение с двойной точностью.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинать брать байты для преобразования |

### Возвращаемое значение

Значение с двойной точностью, полученное в результате преобразования

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) метод


Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в значение с двойной точностью.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинать брать байты для преобразования |

### Возвращаемое значение

Значение с двойной точностью, полученное в результате преобразования

## См. также

* typedef [ArrayPtr](../../arrayptr/)
* класс [BitConverter](../)
* пространство имён [System](../../)
* библиотека [Aspose.Slides](../../../)