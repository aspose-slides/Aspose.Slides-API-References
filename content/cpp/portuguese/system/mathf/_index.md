---
title: MathF
second_title: Aspose.Slides para Referência da API C++
description: Contém funções matemáticas para valores de ponto flutuante de precisão simples. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.
type: docs
weight: 1795
url: /pt/system/mathf/
---
## MathF struct

Contém funções matemáticas para valores de ponto flutuante de precisão simples. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.

```cpp
class MathF
```

## Métodos

| Método | Descrição |
| --- | --- |
| static T [Abs](./abs/)(T) | Retorna o valor absoluto do valor especificado. |
| static **float** [Acos](./acos/)(**float**) | Calcula o arccosseno do valor especificado. |
| static **float** [Asin](./asin/)(**float**) | Calcula o arcseno do valor especificado. |
| static **float** [Atan](./atan/)(**float**) | Calcula o arcotangente do valor especificado. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Calcula o arcotangente da razão dos valores especificados. |
| static **float** [Ceiling](./ceiling/)(**float**) | Retorna o menor valor integral que é maior ou igual ao valor especificado. |
| static **float** [Cos](./cos/)(**float**) | Calcula o cosseno do valor especificado. |
| static **float** [Cosh](./cosh/)(**float**) | Calcula o cosseno hiperbólico do valor especificado. |
| static **float** [Exp](./exp/)(**float**) | Retorna a constante e elevada à potência especificada. |
| static **float** [Floor](./floor/)(**float**) | Retorna o maior valor integral que é menor ou igual ao valor especificado. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Retorna o resto resultante da divisão de um número especificado por outro número especificado. |
| static **float** [Log](./log/)(**float**) | Retorna o logaritmo natural do valor especificado. |
| static **float** [Log](./log/)(**float**, **float**) | Retorna o logaritmo do valor especificado na base especificada. |
| static **float** [Log10](./log10/)(**float**) | Retorna o logaritmo de base 10 do valor especificado. |
| static **float** [Pow](./pow/)(**float**, **float**) | Retorna o valor especificado elevado à potência especificada. |
| static **float** [Round](./round/)(**float**) | Arredonda o valor especificado para o inteiro mais próximo. |
| static **float** [Round](./round/)(**float**, int) | Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o número integral mais próximo. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina o sinal do valor integral assinado especificado. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina o sinal do valor de ponto flutuante especificado. |
| static **float** [Sin](./sin/)(**float**) | Calcula o seno do valor especificado. |
| static **float** [Sinh](./sinh/)(**float**) | Calcula o seno hiperbólico do valor especificado. |
| static **float** [Sqrt](./sqrt/)(**float**) | Retorna a raiz quadrada do valor especificado. |
| static **float** [Tan](./tan/)(**float**) | Calcula a tangente do valor especificado. |
| static **float** [Tanh](./tanh/)(**float**) | Calcula a tangente hiperbólica do valor especificado. |
| static **float** [Truncate](./truncate/)(**float**) | Retorna um valor de ponto flutuante de precisão simples que tem a parte inteira igual à do valor especificado, com todos os dígitos fracionários descartados. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [E](./e/) | Base do logaritmo natural. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | A constante numérica Pi. |
| static [Tau](./tau/) | Valor de Tau. |

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)