---
title: Buffer
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden die ruwe byte-arrays manipuleren. Dit is een statisch type zonder instantieservices. Je mag nooit instanties ervan maken op welke manier dan ook.
type: docs
weight: 144
url: /nl/system/buffer/
---
## Bufferklasse


Bevat methoden die ruwe byte-arrays manipuleren. Dit is een statisch type zonder instantie-services. Je mag nooit instanties ervan maken op welke manier dan ook.

```cpp
class Buffer
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Kopieert een opgegeven aantal bytes van de bronbuffer naar de doelbuffer. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreteert twee opgegeven getypte arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Interpreteert twee opgegeven arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreteert twee opgegeven getypte arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreteert twee opgegeven getypte arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreteert twee opgegeven getypte arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreteert twee opgegeven getypte arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreteert twee opgegeven getypte arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreteert twee opgegeven getypte arrays als ruwe byte-arrays en kopieert gegevens van de ene naar de andere. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Bepaalt het aantal bytes dat door alle elementen van de opgegeven array wordt ingenomen. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Bepaalt het aantal bytes dat door alle elementen van de opgegeven array wordt ingenomen. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Bepaalt het aantal bytes dat door alle elementen van de opgegeven array wordt ingenomen. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Interpreteert de opgegeven getypte array als een ruwe byte-array en haalt de byte-waarde op op de opgegeven byte-offset. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interpreteert de opgegeven getypte array als een ruwe byte-array en haalt de byte-waarde op op de opgegeven byte-offset. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interpreteert de opgegeven getypte array als een ruwe byte-array en haalt de byte-waarde op op de opgegeven byte-offset. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Interpreteert de opgegeven getypte array als een ruwe byte-array en zet de opgegeven byte-waarde op de opgegeven byte-offset. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Interpreteert de opgegeven getypte array als een ruwe byte-array en zet de opgegeven byte-waarde op de opgegeven byte-offset. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Interpreteert de opgegeven getypte array als een ruwe byte-array en zet de opgegeven byte-waarde op de opgegeven byte-offset. |

## Opmerkingen



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
  // Maak en vul de array.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Print de array-items.
  Print(first, SIZE);

  // Maak een array die een deel van de eerste bevat.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Print de items van de tweede array.
  Print(second, SIZE / 2);

  // Stel de waarde van het item op index 0 in en print de array-items.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende uitvoer:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)