---
title: Buffer
second_title: Aspose.Slides C++ API referenciája
description: Tartalmaz olyan metódusokat, amelyek nyers bájt tömböket manipulálnak. Ez egy statikus típus, amely nem rendelkezik példányosított szolgáltatásokkal. Soha ne hozzon létre példányokat ebből semmilyen módon.
type: docs
weight: 144
url: /hu/system/buffer/
---
## Buffer osztály

Tartalmaz olyan metódusokat, amelyek nyers bájt tömböket manipulálnak. Ez egy statikus típus, amely nem rendelkezik példányosított szolgáltatásokkal. Soha ne hozzon létre példányokat ebből semmilyen módon.

```cpp
class Buffer
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Másolja a megadott számú bájtot a forráspufferből a célpufferbe. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Két megadott típusú tömböt nyers bájt tömbökként értelmez, és adatot másol az egyikből a másikba. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Két megadott típusú tömböt nyers bájt tömbökként értelmez, és adatot másol az egyikből a másikba. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Két megadott típusú tömböt nyers bájt tömbökként értelmez, és adatot másol az egyikből a másikba. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Két megadott típusú tömböt nyers bájt tömbökként értelmez, és adatot másol az egyikből a másikba. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Két megadott típusú tömböt nyers bájt tömbökként értelmez, és adatot másol az egyikből a másikba. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Két megadott típusú tömböt nyers bájt tömbökként értelmez, és adatot másol az egyikből a másikba. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Két megadott típusú tömböt nyers bájt tömbökként értelmez, és adatot másol az egyikből a másikba. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Két megadott típusú tömböt nyers bájt tömbökként értelmez, és adatot másol az egyikből a másikba. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Meghatározza a megadott tömb összes elemét elfoglaló bájtok számát. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Meghatározza a megadott tömb összes elemét elfoglaló bájtok számát. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Meghatározza a megadott tömb összes elemét elfoglaló bájtok számát. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájteltolásnál lévő bájt értékét visszaadja. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájteltolásnál lévő bájt értékét visszaadja. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájteltolásnál lévő bájt értékét visszaadja. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájteltolásnál a megadott bájt értékét beállítja. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájteltolásnál a megadott bájt értékét beállítja. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | A megadott típusú tömböt nyers bájt tömbként értelmezi, és a megadott bájteltolásnál a megadott bájt értékét beállítja. |

## Megjegyzések

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
  // Létrehozza és feltölti a tömböt.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Kiírja a tömb elemeit.
  Print(first, SIZE);

  // Létrehoz egy tömböt, amely az első részét tartalmazza.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Kiírja a második tömb elemeit.
  Print(second, SIZE / 2);

  // Beállítja a 0. indexű elem értékét, és kiírja a tömb elemeit.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Ez a kódpélda a következő kimenetet eredményezi:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)