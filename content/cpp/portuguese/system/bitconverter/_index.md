---
title: BitConverter
second_title: Referência da API Aspose.Slides para C++
description: Contém métodos que realizam conversões de sequência de bytes para um tipo de valor e vice-versa. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por quaisquer meios.
type: docs
weight: 66
url: /pt/system/bitconverter/
---
## BitConverter classe

Contém métodos que realizam conversões de sequência de bytes para um tipo de valor e vice-versa. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.

```cpp
class BitConverter
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Indica a ordem de bytes da arquitetura atual. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Retorna um valor inteiro de 64 bits cuja representação binária é igual à representação binária do valor de ponto flutuante de precisão dupla especificado. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Converte o valor booleano especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Converte o valor char_t especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Converte o valor inteiro de 16 bits especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Converte o valor inteiro de 32 bits especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Converte o valor inteiro de 64 bits especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Converte o valor inteiro sem sinal de 16 bits especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Converte o valor inteiro sem sinal de 32 bits especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Converte o valor inteiro sem sinal de 64 bits especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Converte o valor de ponto flutuante de precisão simples especificado em um array de bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Converte o valor de ponto flutuante de precisão dupla especificado em um array de bytes. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Retorna um valor de ponto flutuante de precisão dupla cujo valor é equivalente ao valor. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte um byte do array especificado a partir do índice especificado em um valor booleano. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte um byte do array especificado a partir do índice especificado em um valor booleano. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte dois bytes do array especificado a partir do índice especificado em um valor char_t. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte dois bytes do array especificado a partir do índice especificado em um valor char_t. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte oito bytes do array especificado a partir do índice especificado em um valor de ponto flutuante de precisão dupla. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte oito bytes do array especificado a partir do índice especificado em um valor de ponto flutuante de precisão dupla. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte dois bytes do array especificado a partir do índice especificado em um valor inteiro de 16 bits. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte dois bytes do array especificado a partir do índice especificado em um valor inteiro de 16 bits. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte quatro bytes do array especificado a partir do índice especificado em um valor inteiro de 32 bits. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte quatro bytes do array especificado a partir do índice especificado em um valor inteiro de 32 bits. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte oito bytes do array especificado a partir do índice especificado em um valor inteiro de 64 bits. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte oito bytes do array especificado a partir do índice especificado em um valor inteiro de 64 bits. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte quatro bytes do array especificado a partir do índice especificado em um valor de ponto flutuante de precisão simples. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte quatro bytes do array especificado a partir do índice especificado em um valor de ponto flutuante de precisão simples. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Converte todos os valores do array de bytes especificado em sua representação em string hexadecimal. O caso das letras a ser usado na notação hexadecimal e o separador inserido entre cada par de bytes vizinhos são especificados através dos argumentos correspondentes. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte os valores do array de bytes especificado em sua representação em string hexadecimal a partir do índice especificado. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Converte um intervalo de valores do array de bytes especificado em sua representação em string hexadecimal. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte dois bytes do array especificado a partir do índice especificado em um valor inteiro sem sinal de 16 bits. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte dois bytes do array especificado a partir do índice especificado em um valor inteiro sem sinal de 16 bits. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte quatro bytes do array especificado a partir do índice especificado em um valor inteiro sem sinal de 32 bits. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte quatro bytes do array especificado a partir do índice especificado em um valor inteiro sem sinal de 32 bits. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converte oito bytes do array especificado a partir do índice especificado em um valor inteiro sem sinal de 64 bits. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converte oito bytes do array especificado a partir do índice especificado em um valor inteiro sem sinal de 64 bits. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Indica a ordem de bytes da arquitetura atual. true se a arquitetura for little endian, false caso contrário. |

## Observações



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
  // Criar valores para imprimir.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Imprimir o valor e seus bytes.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)