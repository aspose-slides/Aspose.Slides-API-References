---
title: Sign()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina el signo del valor entero con signo especificado.
type: docs
weight: 274
url: /es/system/math/sign/
---
## Math::Sign(T) método


Determina el signo del valor entero con signo especificado.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo entero con signo |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T | El valor del cual determinar el signo |

### Valor devuelto

- 1 si **value** es menor que 0; 0 si **value** es igual a 0; 1 si **value** es mayor que 0

## Math::Sign(T) método


Determina el signo del valor de punto flotante especificado.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de punto flotante del argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T | El valor del cual determinar el signo |

### Valor devuelto

- 1 si **value** es menor que 0; 0 si **value** es igual a 0; 1 si **value** es mayor que 0

## Math::Sign(const Decimal\&) método


Determina el signo del valor decimal especificado.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | El valor del cual determinar el signo |

### Valor devuelto

- 1 si **value** es menor que 0; 0 si **value** es igual a 0; 1 si **value** es mayor que 0

## Véase también

* Clase [Decimal](../../decimal/)
* Estructura [Math](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)