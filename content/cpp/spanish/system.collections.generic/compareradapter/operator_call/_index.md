---
title: operator()()
second_title: Aspose.Slides para C++ Referencia de API
description: Función de comparación para tipos con operator < disponible.
type: docs
weight: 27
url: /es/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const método

[Comparison](../../../system/comparison/) función para tipos con operator < disponible.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo que se compara; plantilla para disponibilidad de conversión de tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const Q\& | Primer valor a comparar. |
| y | const Q\& | Segundo valor a comparar. |

### Valor de retorno

Verdadero si **x** se considera menor que **y**, falso en caso contrario.

## ComparerAdapter::operator()(const Q\&, const Q\&) const método

[Comparison](../../../system/comparison/) función para tipos con operator < no disponible.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo que se compara; plantilla para disponibilidad de conversión de tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const Q\& | Primer valor a comparar. |
| y | const Q\& | Segundo valor a comparar. |

### Valor de retorno

Verdadero si el comparador está configurado y **x** se considera menor que **y**, falso en caso contrario.

## Ver también

* Estructura [ComparerAdapter](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)