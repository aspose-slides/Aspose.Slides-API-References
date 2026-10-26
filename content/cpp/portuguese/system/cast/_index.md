---
title: Cast()
second_title: Referência da API Aspose.Slides para C++
description: Realiza cast em objetos SmartPtr.
type: docs
weight: 2510
url: /pt/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) função

Realiza cast em objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo apontado de destino. |
| TFrom | Tipo apontado de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Ponteiro de origem. |

### Valor de retorno

Resultado do cast se o cast for permitido.

## Ver também

* Classe [SmartPtr](../smartptr/)
* Estrutura [IsExceptionWrapper](../isexceptionwrapper/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)