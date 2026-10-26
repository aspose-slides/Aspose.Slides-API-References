---
title: CanCast()
second_title: Referência da API Aspose.Slides para C++
description: Verifica a possibilidade de conversão.
type: docs
weight: 40
url: /pt/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) função


Verifica a possibilidade de conversão.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

True quando um valor não nullptr é retornado após a conversão, caso contrário false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) função


Verifica a possibilidade de conversão.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

True quando um valor não nullptr é retornado após a conversão, caso contrário false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) função


Verifica a possibilidade de conversão.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

True quando um valor não nullptr é retornado após a conversão, caso contrário false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) função


Verifica a possibilidade de conversão.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

Sempre retorna true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) função


Verifica a possibilidade de conversão.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

True quando um valor não nullptr é retornado após a conversão, caso contrário false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) função


Verifica a possibilidade de conversão.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

Sempre retorna true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) função


Verifica a possibilidade de conversão.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

True se a operação de conversão foi concluída com sucesso, caso contrário false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) função


Verifica a possibilidade de conversão.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

Sempre retorna false.

## Veja Também

* Struct [CastType](../casttype/)
* Espaço de nomes [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)