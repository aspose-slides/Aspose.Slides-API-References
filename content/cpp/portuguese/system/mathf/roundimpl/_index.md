---
title: RoundImpl()
second_title: Referência da API Aspose.Slides para C++
description: Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.
type: docs
weight: 287
url: /pt/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) método

Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números mais próximos.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **float** | O valor a ser arredondado |
| digits | int | O número de dígitos fracionários no valor arredondado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica como realizar o arredondamento se **value** estiver igualmente próximo de dois números mais próximos. |

### Valor de Retorno

O número com o número especificado de dígitos mais próximo de **value**

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)