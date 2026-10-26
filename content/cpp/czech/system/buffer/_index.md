---
title: Buffer
second_title: Aspose.Slides pro C++ API Reference
description: Obsahuje metody, které manipulují se surovými poli bajtů. Jedná se o statický typ bez služeb instance. Neměli byste jej nikdy vytvářet žádným způsobem.
type: docs
weight: 144
url: /cs/system/buffer/
---
## Buffer třída


Obsahuje metody, které manipulují se surovými poli bajtů. Jedná se o statický typ bez služeb instance. Neměli byste jej nikdy vytvářet žádným způsobem.

```cpp
class Buffer
```

## Metody

| Metoda | Popis |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Zkopíruje zadaný počet bajtů ze zdrojového bufferu do cílového bufferu. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpretuje dva zadané typované pole jako surové pole bajtů a kopíruje data z jednoho do druhého. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Interpretuje dva zadané pole jako surové pole bajtů a kopíruje data z jednoho do druhého. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpretuje dva zadané typované pole jako surové pole bajtů a kopíruje data z jednoho do druhého. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpretuje dva zadané typované pole jako surové pole bajtů a kopíruje data z jednoho do druhého. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpretuje dva zadané typované pole jako surové pole bajtů a kopíruje data z jednoho do druhého. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpretuje dva zadané typované pole jako surové pole bajtů a kopíruje data z jednoho do druhého. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpretuje dva zadané typované pole jako surové pole bajtů a kopíruje data z jednoho do druhého. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpretuje dva zadané typované pole jako surové pole bajtů a kopíruje data z jednoho do druhého. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Určuje počet bajtů obsazených všemi prvky zadaného pole. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Určuje počet bajtů obsazených všemi prvky zadaného pole. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Určuje počet bajtů obsazených všemi prvky zadaného pole. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Interpretuje zadané typované pole jako surové pole bajtů a získá hodnotu bajtu na zadaném posunu bajtů. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interpretuje zadané typované pole jako surové pole bajtů a získá hodnotu bajtu na zadaném posunu bajtů. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interpretuje zadané typované pole jako surové pole bajtů a získá hodnotu bajtu na zadaném posunu bajtů. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Interpretuje zadané typované pole jako surové pole bajtů a nastaví zadanou hodnotu bajtu na zadaném posunu bajtů. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Interpretuje zadané typované pole jako surové pole bajtů a nastaví zadanou hodnotu bajtu na zadaném posunu bajtů. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Interpretuje zadané typované pole jako surové pole bajtů a nastaví zadanou hodnotu bajtu na zadaném posunu bajtů. |
## Poznámky



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
  // Vytvořte a naplňte pole.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Vytiskněte položky pole.
  Print(first, SIZE);

  // Vytvořte pole, které obsahuje část toho prvního.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Vytiskněte položky druhého pole.
  Print(second, SIZE / 2);

  // Nastavte hodnotu položky na indexu 0 a vytiskněte položky pole.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Tento ukázkový kód produkuje následující výstup:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)