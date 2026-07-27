---
title: AreFPNaN()
second_title: Referencia de API de Aspose.Slides para C++
description: namespace Detalles
type: docs
weight: 1
url: /es/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) función


espacio de nombres [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Primer tipo de punto flotante. |
| T2 | Segundo tipo de punto flotante. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | T1 | Primer valor de punto flotante. |
| rhs | T2 | Segundo valor de punto flotante. |

### Valor de retorno

Verdadero si tanto **lhs** como **rhs** son valores de punto flotante, falso en caso contrario.
## Observaciones


Comprueba que dos valores de punto flotante son ambos NaN. Maneja la situación cuando se admite NaN no señalizador. 
## System::TestPredicates::AreFPNaN(T1, T2) función


Comprueba que dos valores de punto flotante son ambos NaN. Maneja la situación cuando NaN no señalizador no es compatible.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Primer tipo de punto flotante. |
| T2 | Segundo tipo de punto flotante. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs | T1 | Primer valor de punto flotante. |
| rhs | T2 | Segundo valor de punto flotante. |

### Valor de retorno

Siempre devuelve falso ya que el valor NaN no es compatible.

## Ver también

* Espacio de nombres [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)