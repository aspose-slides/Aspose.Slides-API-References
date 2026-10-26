---
title: StaticCast_noexcept()
second_title: Referência da API Aspose.Slides para C++
description: Executa cast estático em objetos SmartPtr.
type: docs
weight: 2549
url: /pt/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) função

Executa um cast estático em objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
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

Resultado do cast se a conversão for permitida ou nullptr caso contrário.

Obsoleto
:   Mantido por compatibilidade com versões anteriores. Use AsCast em vez disso.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) função

Executa um cast estático em objetos [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo apontado de destino. |
| TFrom | Tipo apontado de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Ponteiro de origem. |

### Valor de retorno

Resultado do cast se a conversão for permitida ou nullptr caso contrário.

Obsoleto
:   Mantido por compatibilidade com versões anteriores. Use AsCast em vez disso.

## System::StaticCast_noexcept(const TFrom\&) função

Executa um cast estático em objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
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

Resultado do cast se a conversão for permitida ou nullptr caso contrário.

Obsoleto
:   Mantido por compatibilidade com versões anteriores. Use AsCast em vez disso.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) função

Executa um cast estático em Objects para objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
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

Resultado do cast se a conversão for permitida ou nullptr caso contrário.

Obsoleto
:   Mantido por compatibilidade com versões anteriores. Use AsCast em vez disso.

## Veja também

* Classe [SmartPtr](../smartptr/)
* Classe [WeakPtr](../weakptr/)
* Classe [Object](../object/)
* Estrutura [IsExceptionWrapper](../isexceptionwrapper/)
* Estrutura [CastResult](../castresult/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)