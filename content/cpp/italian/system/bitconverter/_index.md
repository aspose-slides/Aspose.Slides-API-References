---
title: BitConverter
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene metodi che eseguono conversioni di sequenze di byte in un tipo valore e viceversa. Si tratta di un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 66
url: /it/system/bitconverter/
---
## BitConverter classe

Contiene metodi che eseguono conversioni di sequenze di byte in un tipo valore e viceversa. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class BitConverter
```

## Metodi

| Method | Description |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Indica l'endianness dell'architettura corrente. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Restituisce un valore intero a 64 bit la cui rappresentazione binaria è uguale alla rappresentazione binaria del valore a virgola mobile double-precision specificato. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Converte il valore booleano specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Converte il valore char_t specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Converte il valore intero a 16 bit specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Converte il valore intero a 32 bit specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Converte il valore intero a 64 bit specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Converte il valore intero senza segno a 16 bit specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Converte il valore intero senza segno a 32 bit specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Converte il valore intero senza segno a 64 bit specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Converte il valore a precisione singola specificato in un array di byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Converte il valore a doppia precisione specificato in un array di byte. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Restituisce un valore a virgola mobile double-precision la cui valore è equivalente al valore fornito. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte un byte dall'array specificato a partire dall'indice specificato in un valore booleano. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte un byte dall'array specificato a partire dall'indice specificato in un valore booleano. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte due byte dall'array specificato a partire dall'indice specificato in un valore char_t. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte due byte dall'array specificato a partire dall'indice specificato in un valore char_t. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte otto byte dall'array specificato a partire dall'indice specificato in un valore a doppia precisione. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte otto byte dall'array specificato a partire dall'indice specificato in un valore a doppia precisione. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero a 16 bit. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero a 16 bit. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero a 32 bit. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero a 32 bit. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte otto byte dall'array specificato a partire dall'indice specificato in un valore intero a 64 bit. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte otto byte dall'array specificato a partire dall'indice specificato in un valore intero a 64 bit. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore a precisione singola. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore a precisione singola. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Converte tutti i valori dell'array di byte specificato nella loro rappresentazione esadecimale. Il caso delle lettere da usare nella notazione esadecimale e il separatore inserito tra coppie di byte adiacenti sono specificati tramite gli argomenti corrispondenti. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte i valori dell'array di byte specificato nella loro rappresentazione esadecimale a partire dall'indice specificato. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Converte un intervallo di valori dell'array di byte specificato nella loro rappresentazione esadecimale. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero senza segno a 16 bit. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte due byte dall'array specificato a partire dall'indice specificato in un valore intero senza segno a 16 bit. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero senza segno a 32 bit. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte quattro byte dall'array specificato a partire dall'indice specificato in un valore intero senza segno a 32 bit. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte otto byte dall'array specificato a partire dall'indice specificato in un valore intero senza segno a 64 bit. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte otto byte dall'array specificato a partire dall'indice specificato in un valore intero senza segno a 64 bit. |

## Campi

| Field | Description |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Indica l'endianness dell'architettura corrente. true se l'architettura è little endian, false altrimenti. |

## Note



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
  // Crea i valori da stampare.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Stampa il valore e i suoi byte.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)