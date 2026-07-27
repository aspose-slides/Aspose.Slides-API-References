---
title: Buffer
second_title: Referência da API Aspose.Slides para C++
description: Contém métodos que manipulam arrays de bytes brutos. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.
type: docs
weight: 144
url: /pt/system/buffer/
---
## Classe Buffer

Contém métodos que manipulam arrays de bytes brutos. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.

```cpp
class Buffer
```

## Métodos

| Método | Descrição |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Copia um número especificado de bytes do buffer de origem para o buffer de destino. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta duas arrays tipadas especificadas como arrays brutos de bytes e copia os dados de uma para a outra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Interpreta duas arrays especificadas como arrays brutos de bytes e copia os dados de uma para a outra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreta duas arrays tipadas especificadas como arrays brutos de bytes e copia os dados de uma para a outra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreta duas arrays tipadas especificadas como arrays brutos de bytes e copia os dados de uma para a outra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta duas arrays tipadas especificadas como arrays brutos de bytes e copia os dados de uma para a outra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreta duas arrays tipadas especificadas como arrays brutos de bytes e copia os dados de uma para a outra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreta duas arrays tipadas especificadas como arrays brutos de bytes e copia os dados de uma para a outra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta duas arrays tipadas especificadas como arrays brutos de bytes e copia os dados de uma para a outra. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Determina o número de bytes ocupados por todos os elementos da array especificada. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Determina o número de bytes ocupados por todos os elementos da array especificada. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Determina o número de bytes ocupados por todos os elementos da array especificada. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Interpreta a array tipada especificada como um array bruto de bytes e obtém o valor do byte no deslocamento de byte especificado. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interpreta a array tipada especificada como um array bruto de bytes e obtém o valor do byte no deslocamento de byte especificado. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interpreta a array tipada especificada como um array bruto de bytes e obtém o valor do byte no deslocamento de byte especificado. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Interpreta a array tipada especificada como um array bruto de bytes e define o valor do byte especificado no deslocamento de byte especificado. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Interpreta a array tipada especificada como um array bruto de bytes e define o valor do byte especificado no deslocamento de byte especificado. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Interpreta a array tipada especificada como um array bruto de bytes e define o valor do byte especificado no deslocamento de byte especificado. |

## Observações

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
  // Crie e preencha o array.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Imprima os itens do array.
  Print(first, SIZE);

  // Crie um array que contém uma parte do primeiro.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Imprima os itens do segundo array.
  Print(second, SIZE / 2);

  // Defina o valor do item no índice 0 e imprima os itens do array.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Ver Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)