---
title: Round()
second_title: Referência da API Aspose.Slides para C++
description: Arredonda o valor especificado para o inteiro mais próximo.
type: docs
weight: 157
url: /pt/system/mathf/round/
---
## MathF::Round(float) método


Arredonda o valor especificado para o inteiro mais próximo.

```cpp
static float System::MathF::Round(float a)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | **float** | O valor a ser arredondado |

### Valor de Retorno

**a** arredondado para o inteiro mais próximo

## MathF::Round(float, int) método


Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários.

```cpp
static float System::MathF::Round(float value, int digits)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **float** | O valor a ser arredondado |
| digits | int | O número de dígitos fracionários no valor arredondado |

### Valor de Retorno

O número com a quantidade especificada de dígitos mais próximo de **value**

## MathF::Round(float, MidpointRounding) método


Arredonda o valor especificado para o número inteiro mais próximo. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **float** | O valor a ser arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como executar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

**value** arredondado para o inteiro mais próximo

## MathF::Round(float, int, MidpointRounding) método


Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **float** | O valor a ser arredondado |
| digits | int | O número de dígitos fracionários no valor arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como executar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

O número com a quantidade especificada de dígitos mais próximo de **value**

## Veja Também

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)