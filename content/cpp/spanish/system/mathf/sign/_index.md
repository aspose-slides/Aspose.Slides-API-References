---
title: Sign()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina el signo del valor entero con signo especificado.
type: docs
weight: 274
url: /es/system/mathf/sign/
---
## MathF::Sign(T) método


Determina el signo del valor entero con signo especificado.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo entero con signo |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T | El value para determinar el signo |

### Valor devuelto

- 1 si **value** es menor que 0; 0 si **value** es igual a 0; 1 si **value** es mayor que 0

## MathF::Sign(T) método


Determina el signo del valor de punto flotante especificado.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de punto flotante del argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T | El value para determinar el signo |

### Valor devuelto

- 1 si **value** es menor que 0; 0 si **value** es igual a 0; 1 si **value** es mayor que 0

## Ver también

* Struct [MathF](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)