---
title: ForceStaticCast()
second_title: Referência da API Aspose.Slides para C++
description: Realiza cast estático real em objetos SmartPtr.
type: docs
weight: 2588
url: /pt/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) função

Realiza cast estático real em objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo apontado de destino. |
| TFrom | Tipo apontado de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Ponteiro de origem. |

### Valor de Retorno

Resultado do cast se o cast for permitido, caso contrário o comportamento é indefinido.

## Veja Também

* Classe [SmartPtr](../smartptr/)
* Estrutura [CastResult](../castresult/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)