---
title: Cast_noexcept()
second_title: Referência da API Aspose.Slides para C++
description: Realiza cast em objetos SmartPtr.
type: docs
weight: 2497
url: /pt/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) função

Realiza cast em objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
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

### Valor de retorno

Resultado do cast se o cast for permitido ou nullptr caso contrário.

## Veja Também

* Classe [SmartPtr](../smartptr/)
* Estrutura [IsExceptionWrapper](../isexceptionwrapper/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)