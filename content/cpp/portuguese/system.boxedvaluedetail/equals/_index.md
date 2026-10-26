---
title: Equals()
second_title: Aspose.Slides para C++ Referência da API
description: Determina a igualdade do valor especificado usando o operador ==().
type: docs
weight: 66
url: /pt/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) função


Determina a igualdade do valor especificado usando [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| The | tipo dos valores sendo comparados |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value1 | T | O primeiro operando |
| value2 | T | O segundo operando |

### Valor de Retorno

True se o valor especificado for igual conforme determinado por [operator==()](../../system/operator_equal_equal/), caso contrário - false

## System::BoxedValueDetail::Equals(T, T) função


Determina a igualdade do valor especificado usando method [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| The | tipo dos valores sendo comparados |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value1 | T | O primeiro operando |
| value2 | T | O segundo operando |

### Valor de Retorno

True se o valor especificado for igual conforme determinado por method [Equals()](./), caso contrário - false

## Veja Também

* Namespace [System::BoxedValueDetail](../)
* Library [Aspose.Slides](../../)