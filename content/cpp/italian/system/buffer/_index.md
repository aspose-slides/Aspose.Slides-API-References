---
title: Buffer
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene metodi che manipolano array di byte grezzi. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 144
url: /it/system/buffer/
---
## Buffer classe

Contiene metodi che manipolano array di byte grezzi. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Buffer
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Copia un numero specificato di byte dal buffer di origine al buffer di destinazione. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Interpreta due array specificati come array grezzi di byte e copia i dati da uno all'altro. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Determina il numero di byte occupati da tutti gli elementi dell'array specificato. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Determina il numero di byte occupati da tutti gli elementi dell'array specificato. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Determina il numero di byte occupati da tutti gli elementi dell'array specificato. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Interpreta l'array tipizzato specificato come un array grezzo di byte e recupera il valore byte all'offset di byte specificato. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interpreta l'array tipizzato specificato come un array grezzo di byte e recupera il valore byte all'offset di byte specificato. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interpreta l'array tipizzato specificato come un array grezzo di byte e recupera il valore byte all'offset di byte specificato. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Interpreta l'array tipizzato specificato come un array grezzo di byte e imposta il valore byte specificato all'offset di byte specificato. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Interpreta l'array tipizzato specificato come un array grezzo di byte e imposta il valore byte specificato all'offset di byte specificato. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Interpreta l'array tipizzato specificato come un array grezzo di byte e imposta il valore byte specificato all'offset di byte specificato. |

## Osservazioni

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
  // Crea e riempi l'array.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Stampa gli elementi dell'array.
  Print(first, SIZE);

  // Crea un array che contiene una parte del primo.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Stampa gli elementi del secondo array.
  Print(second, SIZE / 2);

  // Imposta il valore dell'elemento all'indice 0 e stampa gli elementi dell'array.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)