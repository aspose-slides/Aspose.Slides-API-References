---
title: SafeInvoke()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementación de la traducción del operador '?.'.
type: docs
weight: 2653
url: /es/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) función

Implementación de la traducción del operador '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T0 | expression type. |
| T1 | Type of lambda encapsulating 'WhenTrue' expression. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | T0\&& | expression value. |
| func | T1\&& | 'WhenTrue' expression bound to functor. |

### Valor de retorno

Si el valor de expr no es null, devuelve func llamado con su valor como primer argumento, de lo contrario devuelve null.

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)