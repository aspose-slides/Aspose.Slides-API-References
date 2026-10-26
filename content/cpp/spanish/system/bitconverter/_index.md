---
title: BitConverter
second_title: Referencia de la API de Aspose.Slides para C++
description: Contiene métodos que realizan conversiones de una secuencia de bytes a un tipo de valor y viceversa. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 66
url: /es/system/bitconverter/
---
## BitConverter clase


Contiene métodos que realizan conversiones de una secuencia de bytes a un tipo de valor y viceversa. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class BitConverter
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Indica el endianismo de la arquitectura actual. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Devuelve un valor entero de 64 bits cuya representación binaria es igual a la representación binaria del valor de punto flotante de doble precisión especificado. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Convierte el valor booleano especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Convierte el valor char_t especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Convierte el valor entero de 16 bits especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Convierte el valor entero de 32 bits especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Convierte el valor entero de 64 bits especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Convierte el valor entero sin signo de 16 bits especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Convierte el valor entero sin signo de 32 bits especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Convierte el valor entero sin signo de 64 bits especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Convierte el valor de punto flotante de precisión simple especificado en una matriz de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Convierte el valor de punto flotante de doble precisión especificado en una matriz de bytes. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Devuelve un valor de punto flotante de doble precisión cuyo valor es equivalente al valor. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte un byte del arreglo especificado a partir del índice especificado a un valor booleano. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte un byte del arreglo especificado a partir del índice especificado a un valor booleano. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado a un valor char_t. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado a un valor char_t. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor de punto flotante de doble precisión. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor de punto flotante de doble precisión. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado a un valor entero de 16 bits. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado a un valor entero de 16 bits. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor entero de 32 bits. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor entero de 32 bits. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor entero de 64 bits. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor entero de 64 bits. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor de punto flotante de precisión simple. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor de punto flotante de precisión simple. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Convierte todos los valores del arreglo de bytes especificado a su representación en cadena hexadecimal. El caso de las letras a usar en la notación hexadecimal y el separador insertado entre cada par de bytes adyacentes se especifican mediante los argumentos correspondientes. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte los valores del arreglo de bytes especificado a su representación en cadena hexadecimal comenzando en el índice especificado. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Convierte un rango de valores del arreglo de bytes especificado a su representación en cadena hexadecimal. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 16 bits. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte dos bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 16 bits. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 32 bits. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte cuatro bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 32 bits. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 64 bits. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Convierte ocho bytes del arreglo especificado a partir del índice especificado a un valor entero sin signo de 64 bits. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Indica el endianismo de la arquitectura actual. true si la arquitectura es little endian, false en caso contrario. |

## Observaciones



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
  // Crear valores para imprimir.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Imprimir el valor y sus bytes.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)