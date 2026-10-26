---
title: ExplicitCast()
second_title: Referência da API Aspose.Slides para C++
description: Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado quando o tipo de origem e o tipo de resultado são os mesmos.
type: docs
weight: 2627
url: /pt/system/explicitcast/
---
## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado quando o tipo de origem e o tipo de resultado são os mesmos.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado quando é necessário um cast simples semelhante a um construtor.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para wrappers de exceção.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para converter objeto para exceção.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado quando a origem e o resultado são ponteiros inteligentes (sem SmartPtr<...> explícito no tipo de resultado).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(Source) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado ao converter ponteiro bruto para ponteiro inteligente.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | Source | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado quando a origem e o resultado são ponteiros inteligentes (com SmartPtr<...> explícito no tipo de resultado).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para desempacotar objeto para nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para empacotar nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para desempacotar objeto nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para empacotar enum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para copiar tipos de valor para o heap quando o tipo de valor deve ser referenciado como ponteiro inteligente (em genéricos restritos por interface mas especializados com estrutura que implementa essa interface).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para obter interfaces de tipos de valor.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para empacotamento comum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para empacotamento [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para desempacotar interfaces.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para desempacotamento comum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para cast de nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## System::ExplicitCast(const Source\&) função


Converte o tipo de origem para o tipo de resultado usando cast explícito. Usado para converter entre arrays.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para converter. |

### Valor de Retorno

O resultado da conversão.

## Veja Também

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)