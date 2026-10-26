---
title: ConstCast()
second_title: Referência da API Aspose.Slides para C++
description: Fim de casts obsoletos.
type: docs
weight: 2575
url: /pt/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) função

Fim de casts obsoletos.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo apontado de destino. |
| TFrom | Tipo apontado de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Ponteiro de origem. |

### Valor de retorno

Resultado do cast se o cast for permitido ou nullptr caso contrário.
## Observações

Realiza const cast em objetos [SmartPtr](../smartptr/). 
## Veja também

* Classe [SmartPtr](../smartptr/)
* Estrutura [CastResult](../castresult/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)