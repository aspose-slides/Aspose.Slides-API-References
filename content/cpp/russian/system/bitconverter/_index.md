---
title: BitConverter
second_title: Aspose.Slides для C++ справочник API
description: Содержит методы, которые выполняют преобразования последовательности байтов в тип значения и обратно. Это статический тип без экземплярных служб. Вы никогда не должны создавать его экземпляры каким-либо способом.
type: docs
weight: 66
url: /ru/system/bitconverter/
---
## BitConverter класс

Содержит методы, выполняющие преобразования последовательности байтов в тип значения и обратно. Это статический тип без экземплярных служб. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
class BitConverter
```

## Методы

| Метод | Описание |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Указывает порядок байтов текущей архитектуры. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Возвращает 64-битное целочисленное значение, двоичное представление которого равно двоичному представлению указанного значения двойной точности с плавающей запятой. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Преобразует указанное логическое значение в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Преобразует указанное значение char_t в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Преобразует указанное 16-битное целочисленное значение в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Преобразует указанное 32-битное целочисленное значение в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Преобразует указанное 64-битное целочисленное значение в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Преобразует указанное беззнаковое 16-битное целочисленное значение в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Преобразует указанное беззнаковое 32-битное целочисленное значение в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Преобразует указанное беззнаковое 64-битное целочисленное значение в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Преобразует указанное значение одинарной точности с плавающей запятой в массив байтов. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Преобразует указанное значение двойной точности с плавающей запятой в массив байтов. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Возвращает значение двойной точности с плавающей запятой, эквивалентное указанному значению. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует один байт из указанного массива, начиная с указанного индекса, в логическое значение. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует один байт из указанного массива, начиная с указанного индекса, в логическое значение. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует два байта из указанного массива, начиная с указанного индекса, в значение char_t. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует два байта из указанного массива, начиная с указанного индекса, в значение char_t. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в значение двойной точности с плавающей запятой. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в значение двойной точности с плавающей запятой. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует два байта из указанного массива, начиная с указанного индекса, в 16-битное целочисленное значение. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует два байта из указанного массива, начиная с указанного индекса, в 16-битное целочисленное значение. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует четыре байта из указанного массива, начиная с указанного индекса, в 32-битное целочисленное значение. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует четыре байта из указанного массива, начиная с указанного индекса, в 32-битное целочисленное значение. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в 64-битное целочисленное значение. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в 64-битное целочисленное значение. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует четыре байта из указанного массива, начиная с указанного индекса, в значение одинарной точности с плавающей запятой. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует четыре байта из указанного массива, начиная с указанного индекса, в значение одинарной точности с плавающей запятой. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Преобразует все значения указанного массива байтов в их шестнадцатеричное строковое представление. Регистронезависимость букв в шестнадцатеричном представлении и разделитель, вставляемый между соседними байтами, задаются соответствующими аргументами. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует значения указанного массива байтов в их шестнадцатеричное строковое представление, начиная с указанного индекса. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Преобразует диапазон значений указанного массива байтов в их шестнадцатеричное строковое представление. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует два байта из указанного массива, начиная с указанного индекса, в беззнаковое 16-битное целочисленное значение. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует два байта из указанного массива, начиная с указанного индекса, в беззнаковое 16-битное целочисленное значение. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует четыре байта из указанного массива, начиная с указанного индекса, в беззнаковое 32-битное целочисленное значение. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует четыре байта из указанного массива, начиная с указанного индекса, в беззнаковое 32-битное целочисленное значение. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в беззнаковое 64-битное целочисленное значение. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Преобразует восемь байтов из указанного массива, начиная с указанного индекса, в беззнаковое 64-битное целочисленное значение. |

## Поля

| Поле | Описание |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Указывает порядок байтов текущей архитектуры. true, если архитектура использует порядок little endian, false в противном случае. |

## Примечания



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Создать значения для печати.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Вывести значение и его байты.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Этот пример кода выводит следующее:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)