---
title: ToSingle()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует четыре байта из указанного массива, начиная с указанного индекса, в значение одинарной точности с плавающей запятой.
type: docs
weight: 131
url: /ru/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) метод


Преобразует четыре байта из указанного массива, начиная с указанного индекса, в число одинарной точности с плавающей запятой.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинаются байты для преобразования |

### Возвращаемое значение

Число одинарной точности с плавающей запятой, полученное в результате преобразования

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) метод


Преобразует четыре байта из указанного массива, начиная с указанного индекса, в число одинарной точности с плавающей запятой.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, содержащий байты для преобразования |
| startIndex | int | Индекс в массиве, с которого начинаются байты для преобразования |

### Возвращаемое значение

Число одинарной точности с плавающей запятой, полученное в результате преобразования

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)