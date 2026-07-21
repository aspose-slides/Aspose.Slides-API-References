---
title: Buffer
second_title: Справочник API Aspose.Slides для C++
description: Содержит методы, которые манипулируют массивами необработанных байтов. Это статический тип без служб экземпляра. Вы никогда не должны создавать его экземпляры любой ценой.
type: docs
weight: 144
url: /ru/system/buffer/
---
## Класс Buffer


Содержит методы, которые работают с массивами необработанных байтов. Это статический тип без служб экземпляра. Вы никогда не должны создавать его экземпляры любой ценой.

```cpp
class Buffer
```

## Методы

| Method | Description |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Копирует указанное количество байтов из исходного буфера в целевой буфер. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Определяет количество байтов, занимаемых всеми элементами указанного массива. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Определяет количество байтов, занимаемых всеми элементами указанного массива. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Определяет количество байтов, занимаемых всеми элементами указанного массива. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Интерпретирует указанный типизированный массив как массив необработанных байтов и получает значение байта по указанному смещению. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Интерпретирует указанный типизированный массив как массив необработанных байтов и получает значение байта по указанному смещению. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Интерпретирует указанный типизированный массив как массив необработанных байтов и получает значение байта по указанному смещению. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Интерпретирует указанный типизированный массив как массив необработанных байтов и устанавливает указанное значение байта по указанному смещению. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Интерпретирует указанный типизированный массив как массив необработанных байтов и устанавливает указанное значение байта по указанному смещению. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Интерпретирует указанный типизированный массив как массив необработанных байтов и устанавливает указанное значение байта по указанному смещению. |

## Примечания



```cpp
#include <system/buffer.h>

using namespace System;

void Print(const SmartPtr<Array<uint8_t>> &source, int size)
{
  for (auto i = 0; i < size; i++)
  {
    std::cout << static_cast<int>(source[i]) << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Создать и заполнить массив.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Вывести элементы массива.
  Print(first, SIZE);

  // Создать массив, содержащий часть первого.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Вывести элементы второго массива.
  Print(second, SIZE / 2);

  // Установить значение элемента с индексом 0 и вывести элементы массива.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Этот пример кода выводит следующее:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Смотрите также

* Пространство имен [System](../)
* Library [Aspose.Slides](../../)