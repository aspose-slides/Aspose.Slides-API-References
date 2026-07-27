---
title: Is()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementa la traducción del patrón de declaración 'is'.
type: docs
weight: 2302
url: /es/system/is/
---
## System::Is(const ExpressionT&, ResultT&) function


Implementa la traducción del patrón de declaración 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| PatternT | tipo a comprobar. |
| ExpressionT | tipo de expresión izquierda. |
| ResultT | tipo de expresión de resultado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | const ExpressionT& | expresión que será verificada. |
| result | ResultT& | variable a la que se asignará el tipo verificado. |

### Valor de retorno

true if type check is successful, false otherwise.

## System::Is(const ExpressionT&, const ConstantT&) function


Implementa la traducción del patrón constante 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ExpressionT | tipo de expresión izquierda. |
| ConstantT | tipo de expresión constante. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | const ExpressionT& | expresión que será verificada. |
| constant | const ConstantT& | expresión que será comparada con la de la izquierda. |

### Valor de retorno

true if type check is successful, false otherwise.

## System::Is(const E&, const A&) function


Función de coincidencia de nivel superior. Aplica un patrón a un valor.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| A | Tipo de patrón (debe heredar de Details::Pattern). |
| E | Tipo del valor a coincidir. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| e | const E& | Valor contra el cual coincidir. |
| a | const A& | Patrón a aplicar. |

### Valor de retorno

true if the pattern matches the value.

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)