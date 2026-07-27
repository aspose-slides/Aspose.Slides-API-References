---
title: Math
second_title: Referência da API Aspose.Slides para C++
description: Contém funções matemáticas. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele de qualquer forma.
type: docs
weight: 1782
url: /pt/system/math/
---
## Math struct


Contém funções matemáticas. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele de qualquer forma.

```cpp
class Math
```

## Métodos

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Retorna o valor absoluto do valor especificado. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Retorna o valor absoluto de um valor representado pelo objeto [Decimal](../decimal/) especificado. |
| static **double** [Acos](./acos/)(**double**) | Calcula o arco cosseno do valor especificado. |
| static **double** [Asin](./asin/)(**double**) | Calcula o arco seno do valor especificado. |
| static **double** [Atan](./atan/)(**double**) | Calcula o arco tangente do valor especificado. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Calcula o arco tangente da razão dos valores especificados. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Retorna o produto completo de dois inteiros de 32 bits. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Retorna o menor valor integral que é maior ou igual ao valor especificado. |
| static **double** [Ceiling](./ceiling/)(**double**) | Retorna o menor valor integral que é maior ou igual ao valor especificado. |
| static **double** [Cos](./cos/)(**double**) | Calcula o cosseno do valor especificado. |
| static **double** [Cosh](./cosh/)(**double**) | Calcula o cosseno hiperbólico do valor especificado. |
| static int [DivRem](./divrem/)(int, int, int\&) | Calcula o quociente de dois inteiros de 32 bits e o resto. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Calcula o quociente de dois inteiros de 64 bits e o resto. |
| static **double** [Exp](./exp/)(**double**) | Retorna a constante e elevada à potência especificada. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Retorna o maior valor integral que é menor ou igual ao valor especificado. |
| static **double** [Floor](./floor/)(**double**) | Retorna o maior valor integral que é menor ou igual ao valor especificado. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Retorna o resto resultante da divisão de um número especificado por outro número especificado. |
| static **double** [Log](./log/)(**double**) | Retorna o logaritmo natural do valor especificado. |
| static **double** [Log](./log/)(**double**, **double**) | Retorna o logaritmo do valor especificado na base especificada. |
| static **double** [Log10](./log10/)(**double**) | Retorna o logaritmo base 10 do valor especificado. |
| static auto [Max](./max/)(T0, T1) | Retorna o maior valor entre dois valores numéricos especificados. |
| static T0 [Max](./max/)(T0, T1) | Retorna o maior valor entre dois valores numéricos especificados. |
| **float** [Max_](./max_/)(**float**, **float**) | Retorna o maior valor de ponto flutuante de precisão simples dos dois especificados. |
| **double** [Max_](./max_/)(**double**, **double**) | Retorna o maior valor de ponto flutuante de precisão dupla dos dois especificados. |
| static auto [Min](./min/)(T0, T1) | Retorna o menor valor entre dois valores numéricos especificados. |
| static T0 [Min](./min/)(T0, T1) | Retorna o menor valor entre dois valores numéricos especificados. |
| **float** [Min_](./min_/)(**float**, **float**) | Retorna o menor valor de ponto flutuante de precisão simples dos dois especificados. |
| **double** [Min_](./min_/)(**double**, **double**) | Retorna o menor valor de ponto flutuante de precisão dupla dos dois especificados. |
| static T [Modulus](./modulus/)(T, T) | Calcula o resto resultante da divisão de um valor especificado por outro valor especificado. |
| static **double** [Pow](./pow/)(**double**, **double**) | Retorna o valor especificado elevado à potência especificada. |
| static **double** [Round](./round/)(**double**) | Arredonda o valor especificado para o inteiro mais próximo. |
| static **double** [Round](./round/)(**double**, int) | Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver equidistante dos dois números mais próximos. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o número inteiro mais próximo. Um parâmetro especifica o comportamento da função se o valor especificado estiver equidistante dos dois números mais próximos. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver equidistante dos dois números mais próximos. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Arredonda o valor especificado para o inteiro mais próximo. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver equidistante dos dois números mais próximos. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o número inteiro mais próximo. Um parâmetro especifica o comportamento da função se o valor especificado estiver equidistante dos dois números mais próximos. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver equidistante dos dois números mais próximos. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina o sinal do valor integral assinado especificado. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina o sinal do valor de ponto flutuante especificado. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Determina o sinal do valor decimal especificado. |
| static **double** [Sin](./sin/)(**double**) | Calcula o seno do valor especificado. |
| static **double** [Sinh](./sinh/)(**double**) | Calcula o seno hiperbólico do valor especificado. |
| static **double** [Sqrt](./sqrt/)(**double**) | Retorna a raiz quadrada do valor especificado. |
| static **double** [Tan](./tan/)(**double**) | Calcula a tangente do valor especificado. |
| static **double** [Tanh](./tanh/)(**double**) | Calcula a tangente hiperbólica do valor especificado. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Retorna o objeto [Decimal](../decimal/) que representa um valor cujo parte integral é igual à parte integral do valor representado pelo objeto [Decimal](../decimal/) especificado, com todos os dígitos fracionários descartados. |
| static **double** [Truncate](./truncate/)(**double**) | Retorna um valor de ponto flutuante de precisão dupla cujo parte integral é igual à parte integral do valor especificado, com todos os dígitos fracionários descartados. |

## Campos

| Field | Description |
| --- | --- |
| static [E](./e/) | Base do logaritmo natural. |
| static [NaN](./nan/) | Representa um valor NaN (não é número). |
| static [NegativeInfinity](./negativeinfinity/) | Representa o infinito negativo. |
| static [PI](./pi/) | A constante Pi. |
| static [PositiveInfinity](./positiveinfinity/) | Representa o infinito positivo. |

## Observações



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Imprime os valores absolutos.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Imprime o seno de PI/2 e o cosseno de PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Veja Também

* Namespace [System](../)
* Library [Aspose.Slides](../../)