---
title: Buffer
second_title: Odwołanie do API Aspose.Slides dla C++
description: Zawiera metody, które manipulują surowymi tablicami bajtów. Jest to typ statyczny bez usług instancji. Nie należy tworzyć jego instancji w żaden sposób.
type: docs
weight: 144
url: /pl/system/buffer/
---
## Klasa Buffer


Zawiera metody, które manipulują surowymi tablicami bajtów. Jest to typ statyczny bez usług instancji. Nie powinno się tworzyć jego instancji w żaden sposób.

```cpp
class Buffer
```

## Metody

| Metoda | Opis |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Kopiuje określoną liczbę bajtów z bufora źródłowego do bufora docelowego. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuj dane z jednej do drugiej. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuj dane z jednej do drugiej. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuj dane z jednej do drugiej. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuj dane z jednej do drugiej. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuj dane z jednej do drugiej. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuj dane z jednej do drugiej. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuj dane z jednej do drugiej. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuj dane z jednej do drugiej. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Określa liczbę bajtów zajmowaną przez wszystkie elementy określonej tablicy. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Określa liczbę bajtów zajmowaną przez wszystkie elementy określonej tablicy. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Określa liczbę bajtów zajmowaną przez wszystkie elementy określonej tablicy. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Interpretuj określoną tablicę typowaną jako surową tablicę bajtów i pobierz wartość bajtu pod określonym przesunięciem bajtowym. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interpretuj określoną tablicę typowaną jako surową tablicę bajtów i pobierz wartość bajtu pod określonym przesunięciem bajtowym. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interpretuj określoną tablicę typowaną jako surową tablicę bajtów i pobierz wartość bajtu pod określonym przesunięciem bajtowym. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Interpretuj określoną tablicę typowaną jako surową tablicę bajtów i ustaw określoną wartość bajtu pod określonym przesunięciem bajtowym. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Interpretuj określoną tablicę typowaną jako surową tablicę bajtów i ustaw określoną wartość bajtu pod określonym przesunięciem bajtowym. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Interpretuj określoną tablicę typowaną jako surową tablicę bajtów i ustaw określoną wartość bajtu pod określonym przesunięciem bajtowym. |
## Uwagi



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
  // Utwórz i wypełnij tablicę.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Wypisz elementy tablicy.
  Print(first, SIZE);

  // Utwórz tablicę, która zawiera część pierwszej.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Wypisz elementy drugiej tablicy.
  Print(second, SIZE / 2);

  // Ustaw wartość elementu o indeksie 0 i wypisz elementy tablicy.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Ten przykład kodu generuje następujące wyjście:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)