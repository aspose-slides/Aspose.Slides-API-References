---
title: DynamicCast_noexcept()
second_title: Referência da API Aspose.Slides para C++
description: Conversões antigas e obsoletas. Serão removidas em versões futuras.
type: docs
weight: 2523
url: /pt/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) função


Conversões antigas e obsoletas. Serão removidas em versões futuras.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo de exceção de destino. |
| TFrom | Tipo de exceção de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const TFrom\& | Ponteiro de origem. |

### Valor de retorno

Resultado do cast se o cast for permitido ou nullptr caso contrário.
## Observações


Realiza cast dinâmico em objetos Exception. Obsoleto
:   Mantido para compatibilidade retroativa. Use AsCast em vez disso.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) função


Realiza cast dinâmico em objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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

Obsoleto
:   Mantido para compatibilidade retroativa. Use AsCast em vez disso.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) função


Realiza cast dinâmico em Objects para objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo de exceção de destino. |
| TFrom | [Object](../object/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Ponteiro de origem. |

### Valor de retorno

Resultado do cast se o cast for permitido ou nullptr caso contrário.

Obsoleto
:   Mantido para compatibilidade retroativa. Use AsCast em vez disso.

## Veja Também

* Classe [SmartPtr](../smartptr/)
* Classe [Object](../object/)
* Estrutura [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)