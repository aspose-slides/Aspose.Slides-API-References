---
title: DynamicCast()
second_title: Referência da API Aspose.Slides para C++
description: Executa cast dinâmico em objetos Exception.
type: docs
weight: 2536
url: /pt/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) função

Executa cast dinâmico em objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo Exception de destino. |
| TFrom | Tipo Exception de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const TFrom\& | Ponteiro de origem. |

### Valor de retorno

Resultado do cast se o cast for permitido.

Obsoleto
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) função

Executa cast dinâmico em objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
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

Resultado do cast se o cast for permitido.

Obsoleto
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::DynamicCast(SmartPtr\<TFrom\>) função

Desempacota enum encapsulado via cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo enum de destino. |
| TFrom | Tipo apontado de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Ponteiro para o objeto do qual desempacotar os dados. |

### Valor de retorno

Valor do enum desempacotado.

Obsoleto
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::DynamicCast(std::nullptr_t) função

Executa cast dinâmico de objetos nulos.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo apontado de destino. |

### Valor de retorno

nullptr.

Obsoleto
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::DynamicCast(TFrom\&) função

Executa cast dinâmico em objetos não ponteiro.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo de destino. |
| TFrom | Tipo de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | TFrom\& | Objeto de origem. |

### Valor de retorno

Resultado do cast.

Obsoleto
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::DynamicCast(SmartPtr\<TFrom\>) função

Executa cast dinâmico em Objects para objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo Exception de destino. |
| TFrom | Tipo [Object](../object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Ponteiro de origem. |

### Valor de retorno

Resultado do cast se o cast for permitido.

Obsoleto
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::DynamicCast(TFrom) função

Executa cast dinâmico de IntPtr para ponteiro.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo de destino. |
| TFrom | Tipo de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | TFrom | Valor IntPtr de origem. |

### Valor de retorno

Resultado do cast.

Obsoleto
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## Veja Também

* Classe [SmartPtr](../smartptr/)
* Classe [Object](../object/)
* Estrutura [IsExceptionWrapper](../isexceptionwrapper/)
* Estrutura [CastResult](../castresult/)
* Estrutura [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)