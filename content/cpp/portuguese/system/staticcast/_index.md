---
title: StaticCast()
second_title: Referência da API Aspose.Slides para C++
description: Realiza cast estático em objetos SmartPtr.
type: docs
weight: 2562
url: /pt/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) função

Realiza cast estático em objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
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

Resultado do cast se o cast for permitido.

Descontinuado
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::StaticCast(WeakPtr\<TFrom\> const\&) função

Realiza cast estático em objetos [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
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

### Valor de Retorno

Resultado do cast se o cast for permitido.

Descontinuado
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::StaticCast(std::nullptr_t) função

Realiza cast estático de objetos nulos.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo apontado de destino. |

### Valor de Retorno

nullptr.

Descontinuado
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::StaticCast(TFrom) função

Especialização para tipos aritméticos.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) função

Processa cast de [String](../string/) para [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) função

Especialização para tipos aritméticos.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) função

Realiza cast estático em objetos não ponteiro.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo de destino. |
| TFrom | Tipo de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const TFrom\& | Objeto de origem. |

### Valor de Retorno

Resultado do cast se o cast for permitido.

Descontinuado
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::StaticCast(const TFrom\&) função

Realiza cast estático em objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
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

### Valor de Retorno

Resultado do cast se o cast for permitido.

Descontinuado
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::StaticCast(SmartPtr\<TFrom\>) função

Realiza cast estático em Objects para objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TTo | Tipo Exception de destino. |
| TFrom | [Object](../object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Ponteiro de origem. |

### Valor de Retorno

Resultado do cast se o cast for permitido.

Descontinuado
:   Mantido por compatibilidade retroativa. Use ExplicitCast em vez disso.

## Ver também

* Class [SmartPtr](../smartptr/)
* Class [WeakPtr](../weakptr/)
* Class [String](../string/)
* Class [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [CastResult](../castresult/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)