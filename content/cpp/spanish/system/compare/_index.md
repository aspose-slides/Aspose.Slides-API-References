---
title: Compare()
second_title: Aspose.Slides para C++ Referencia de API
description: Compara dos valores.
type: docs
weight: 2731
url: /es/system/compare/
---
## System::Compare(const TA\&, const TB\&) función


Compara dos valores.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TA | El tipo del primer comparando |
| TB | El tipo del segundo comparando |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const TA\& | El primer comparando |
| b | const TB\& | El segundo comparando |

### Valor de retorno

- 1 si **a** es menor que **b**; 0 si los valores son iguales; 1 si **a** es mayor que **b**

## System::Compare(const TA\&, const TB\&) función


Compara dos valores de punto flotante.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TA | El tipo del primer comparando |
| TB | El tipo del segundo comparando |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const TA\& | El primer comparando |
| b | const TB\& | El segundo comparando |

### Valor de retorno

- 1 si **a** es menor que **b**; 0 si los valores son iguales; 1 si **a** es mayor que **b**

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)