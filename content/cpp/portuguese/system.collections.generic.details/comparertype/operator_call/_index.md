---
title: operator()()
second_title: Referência da API Aspose.Slides para C++
description: Compara tipos de valor que implementam a interface IComparable.
type: docs
weight: 1
url: /pt/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const método

Compara tipos de valor que implementam a interface [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo a ser comparado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const Q\& | Valor LHS. |
| b | const Q\& | Valor RHS. |

### Valor de retorno

Verdadeiro se **a** for considerado menor que **b**, falso caso contrário.

## ComparerType::operator()(const Q\&, const Q\&) const método

Compara tipos de valor primitivos e objetos que não implementam a interface [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo a ser comparado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const Q\& | Valor LHS. |
| b | const Q\& | Valor RHS. |

### Valor de retorno

Verdadeiro se **a** for considerado menor que **b**, falso caso contrário.

## ComparerType::operator()(const Q\&, const Q\&) const método

Compara tipos de ponto flutuante.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo a ser comparado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const Q\& | Valor LHS. |
| b | const Q\& | Valor RHS. |

### Valor de retorno

Verdadeiro se **a** for considerado menor que **b**, falso caso contrário.

## Veja também

* Classe [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto](../../has_method_compareto/)
* Struct [ComparerType](../)
* Espaço de nomes [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)