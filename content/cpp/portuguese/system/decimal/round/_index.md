---
title: Round()
second_title: Aspose.Slides para C++ Referência da API
description: Arredonda o valor especificado para o número inteiro mais próximo. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.
type: docs
weight: 404
url: /pt/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) método

Arredonda o valor especificado para o número inteiro mais próximo. Um parâmetro especifica o comportamento da função se **value** estiver igualmente próximo de dois números mais próximos.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | const [Decimal](../)\& | O valor a ser arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como realizar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

**d** arredondado para o valor inteiro mais próximo

## Decimal::Round(const Decimal\&, int, MidpointRounding) método

Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se **value** estiver igualmente próximo de dois números mais próximos.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | const [Decimal](../)\& | O valor a ser arredondado |
| digits | int | O número de dígitos fracionários no valor arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como realizar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

O número com o número especificado de dígitos mais próximo de **value**

## Veja Também

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)