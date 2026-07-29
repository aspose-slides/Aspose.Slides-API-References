---
title: Buffer
second_title: Aspose.Slides för C++ API-referens
description: Innehåller metoder som manipulerar råa byte-arrayer. Detta är en statisk typ utan instanstjänster. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 144
url: /sv/system/buffer/
---
## Buffer klass

Innehåller metoder som hanterar råa byte-arrayer. Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Buffer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Kopierar ett specificerat antal byte från källbuffert till destinationsbuffert. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Tolkar två specificerade typade arrayer som råa byte-arrayer och kopierar data från den ena till den andra. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Bestämmer antalet byte som upptas av alla element i den specificerade arrayen. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Bestämmer antalet byte som upptas av alla element i den specificerade arrayen. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Bestämmer antalet byte som upptas av alla element i den specificerade arrayen. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Tolkar den specificerade typade arrayen som en rå byte-array och hämtar bytevärdet vid den specificerade byte-offseten. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Tolkar den specificerade typade arrayen som en rå byte-array och hämtar bytevärdet vid den specificerade byte-offseten. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Tolkar den specificerade typade arrayen som en rå byte-array och hämtar bytevärdet vid den specificerade byte-offseten. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Tolkar den specificerade typade arrayen som en rå byte-array och sätter det specificerade bytevärdet vid den specificerade byte-offseten. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Tolkar den specificerade typade arrayen som en rå byte-array och sätter det specificerade bytevärdet vid den specificerade byte-offseten. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Tolkar den specificerade typade arrayen som en rå byte-array och sätter det specificerade bytevärdet vid den specificerade byte-offseten. |

## Anmärkningar

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
  // Skapa och fyll arrayen.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Skriv ut arrayens element.
  Print(first, SIZE);

  // Skapa en array som innehåller en del av den första.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Skriv ut elementen i den andra arrayen.
  Print(second, SIZE / 2);

  // Sätt värdet på elementet på index 0 och skriv ut arrayens element.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Detta kodexempel producerar följande utdata:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)