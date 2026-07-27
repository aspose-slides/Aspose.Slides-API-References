---
title: Is()
second_title: Referência da API Aspose.Slides para C++
description: Implementa a tradução do padrão de declaração 'is'.
type: docs
weight: 2302
url: /pt/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) função

Implementa a tradução do padrão de declaração 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| PatternT | tipo a ser verificado. |
| ExpressionT | tipo da expressão esquerda. |
| ResultT | tipo da expressão de resultado. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | expressão que será verificada. |
| result | ResultT\& | variável que receberá o tipo verificado. |

### Valor de Retorno

true se a verificação de tipo for bem-sucedida, false caso contrário.

## System::Is(const ExpressionT\&, const ConstantT\&) função

Implementa a tradução do padrão constante 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| ExpressionT | tipo da expressão esquerda. |
| ConstantT | tipo da expressão constante. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | expressão que será verificada. |
| constant | const ConstantT\& | expressão que será comparada com a da esquerda. |

### Valor de Retorno

true se a verificação de tipo for bem-sucedida, false caso contrário.

## System::Is(const E\&, const A\&) função

Função de correspondência de nível superior. Aplica um padrão a um valor.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| A | Tipo de padrão (deve herdar de Details::Pattern). |
| E | Tipo do valor a ser correspondido. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| e | const E\& | Valor contra o qual corresponder. |
| a | const A\& | Padrão a ser aplicado. |

### Valor de Retorno

true se o padrão corresponder ao valor.

## Veja Também

* Namespace [System](../)
* Library [Aspose.Slides](../../)