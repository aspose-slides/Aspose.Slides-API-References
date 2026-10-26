---
title: Cast()
second_title: Referência da API Aspose.Slides para C++
description: Converte o tipo de origem para o tipo de resultado. Usado quando os tipos de origem e de resultado são os mesmos.
type: docs
weight: 14
url: /pt/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) function

Converte o tipo de origem para o tipo de resultado. Usado quando os tipos de origem e de resultado são os mesmos.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

O resultado da conversão.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem pode ser convertido estaticamente para o tipo de resultado.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

O resultado da conversão.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Converte o tipo de origem para o tipo de resultado. Usado quando os tipos não são iguais e o tipo de origem não pode ser convertido estaticamente para o tipo de resultado.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

O resultado da conversão.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem está sendo encapsulado na instância da classe [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

O resultado da conversão.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem está sendo desencapsulado da instância da classe [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

O resultado da conversão.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem está sendo encapsulado na instância da classe [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

O resultado da conversão.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem está sendo desencapsulado da instância da classe [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

O resultado da conversão.

## System::Collections::Generic::Details::CastRules::Cast(Source) function

Converte o tipo de origem para o tipo de resultado. Usado quando a conversão é inválida ou a conversão é explícita.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Source | O tipo de origem. |
| Result | O tipo de resultado. |

### Valor de retorno

O resultado da conversão.

## Veja também

* Estrutura [CastType](../casttype/)
* Espaço de nomes [System::Collections::Generic::Details::CastRules](../)
* Biblioteca [Aspose.Slides](../../)