---
title: operator()()
second_title: Referência da API Aspose.Slides para C++
description: Função de comparação para tipos com operador < disponível.
type: docs
weight: 27
url: /pt/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const método


[Comparison](../../../system/comparison/) função para tipos com operador < disponível.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo sendo comparado; modelo para disponibilidade de conversão de tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const Q\& | Primeiro valor a comparar. |
| y | const Q\& | Segundo valor a comparar. |

### Valor de retorno

Verdadeiro se **x** for considerado menor que **y**, falso caso contrário.

## ComparerAdapter::operator()(const Q\&, const Q\&) const método


[Comparison](../../../system/comparison/) função para tipos com operador < não disponível.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo sendo comparado; modelo para disponibilidade de conversão de tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const Q\& | Primeiro valor a comparar. |
| y | const Q\& | Segundo valor a comparar. |

### Valor de retorno

Verdadeiro se o comparador estiver definido e **x** for considerado menor que **y**, falso caso contrário.

## Veja Também

* Estrutura [ComparerAdapter](../)
* Espaço de nomes [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)