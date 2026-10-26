---
title: AsCast()
second_title: Referência da API Aspose.Slides para C++
description: Converte o tipo de origem para o tipo de resultado usando o operador de cast 'as'. Usado quando é necessário um cast simples semelhante a um construtor.
type: docs
weight: 2640
url: /pt/system/ascast/
---
## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado quando um cast simples semelhante a um construtor é necessário.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado quando os tipos de origem e de resultado são os mesmos.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para wrappers de exceção.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast. Retorna nullptr se nenhuma conversão estiver disponível.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para converter objeto para exceção.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast. Retorna nullptr se nenhuma conversão estiver disponível.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado quando origem e resultado são ambos ponteiros inteligentes.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast. Retorna nullptr se nenhuma conversão estiver disponível.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado quando origem e resultado são ambos ponteiros inteligentes (com SmartPtr<...> explícito no tipo de resultado).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast. Retorna nullptr se nenhuma conversão estiver disponível.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para desempacotar objeto para um nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast. Retorna nullable vazio se nenhuma conversão estiver disponível.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Desempacotamento inválido para tipo não-objeto.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
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

### Valor de retorno

Sempre retorna nulo.

## System::AsCast(const Source\&) função

Desempacotamento inválido para tipo não-objeto.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
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

### Valor de retorno

Sempre retorna nulo.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para empacotar objeto nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para empacotar objeto comum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para empacotar objeto comum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para desempacotar string.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para tratamento de nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast.

## System::AsCast(const Source\&) função

Converte o tipo de origem para o tipo de resultado usando o operador de cast ‘as’. Usado para converter entre arrays.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

### Valor de retorno

O resultado do cast. Retorna nullptr se nenhuma conversão estiver disponível para nenhum membro do array.

## Veja também

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)