---
title: Buffer
second_title: Referencia de la API de Aspose.Slides para C++
description: Contiene métodos que manipulan matrices de bytes crudos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 144
url: /es/system/buffer/
---
## Clase Buffer

Contains methods that manipulate raw byte arrays. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Buffer
```

## Métodos

| Método | Descripción |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Copia un número especificado de bytes del búfer de origen al búfer de destino. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia los datos de una a otra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Interpreta dos matrices especificadas como matrices crudas de bytes y copia los datos de una a otra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia los datos de una a otra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia los datos de una a otra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia los datos de una a otra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia los datos de una a otra. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia los datos de una a otra. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia los datos de una a otra. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Determina el número de bytes ocupados por todos los elementos de la matriz especificada. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Determina el número de bytes ocupados por todos los elementos de la matriz especificada. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Determina el número de bytes ocupados por todos los elementos de la matriz especificada. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y recupera el valor del byte en el desplazamiento de byte especificado. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Interpreta la matriz tipada especificada como una matriz cruda de bytes y establece el valor del byte especificado en el desplazamiento de byte especificado. |

## Observaciones

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
  // Crear y rellenar la matriz.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Imprimir los elementos de la matriz.
  Print(first, SIZE);

  // Crear una matriz que contiene una parte de la primera.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Imprimir los elementos de la segunda matriz.
  Print(second, SIZE / 2);

  // Establecer el valor del elemento en el índice 0 e imprimir los elementos de la matriz.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)