---
title: Round()
second_title: Referência da API Aspose.Slides para C++
description: Arredonda o valor especificado para o inteiro mais próximo.
type: docs
weight: 157
url: /pt/system/math/round/
---
## Math::Round(double) método

Arredonda o valor especificado para o inteiro mais próximo.

```cpp
static double System::Math::Round(double a)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | **double** | O valor a ser arredondado |

### Valor de Retorno

**a** arredondado para o inteiro mais próximo

## Math::Round(double, int) método

Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários.

```cpp
static double System::Math::Round(double value, int digits)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **double** | O valor a ser arredondado |
| digits | int | O número de dígitos fracionários no valor arredondado |

### Valor de Retorno

O número com o número especificado de dígitos mais próximo de **value**

## Math::Round(double, MidpointRounding) método

Arredonda o valor especificado para o número inteiro mais próximo. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **double** | O valor a ser arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como executar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

**value** arredondado para o inteiro mais próximo

## Math::Round(double, int, MidpointRounding) método

Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **double** | O valor a ser arredondado |
| digits | int | O número de dígitos fracionários no valor arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como executar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

O número com o número especificado de dígitos mais próximo de **value**

## Math::Round(const Decimal\&) método

Arredonda o valor especificado para o inteiro mais próximo.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | O valor a ser arredondado |

### Valor de Retorno

**d** arredondado para o inteiro mais próximo

## Math::Round(const Decimal\&, int) método

Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | O valor a ser arredondado |
| digits | int | O número de dígitos fracionários no valor arredondado |

### Valor de Retorno

O número com o número especificado de dígitos mais próximo de **value**

## Math::Round(const Decimal\&, MidpointRounding) método

Arredonda o valor especificado para o número inteiro mais próximo. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | O valor a ser arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como executar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

**d** arredondado para o inteiro mais próximo

## Math::Round(const Decimal\&, int, MidpointRounding) método

Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | O valor a ser arredondado |
| digits | int | O número de dígitos fracionários no valor arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como executar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

O número com o número especificado de dígitos mais próximo de **value**

## Veja Também

* Enum [MidpointRounding](../../midpointrounding/)
* Classe [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)