---
title: Equals< float, float >()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especialización para valores de punto flotante de precisión simple. Aunque dos NaNs de punto flotante están definidos por IEC 60559:1989 para compararse siempre como desiguales, el contrato para System.Object.Equals, requiere que las sobrescrituras cumplan los requisitos de un operador de equivalencia. Por lo tanto, System.Double.Equals y System.Single.Equals devuelven True al comparar dos NaNs, mientras que el operador de igualdad devuelve False en ese caso, según lo requerido por el estándar."
type: docs
weight: 2705
url: /es/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) función

Especialización para valores de punto flotante de precisión simple. Aunque dos NaNs de punto flotante están definidos por IEC 60559:1989 para compararse siempre como desiguales, el contrato para [System.Object.Equals](../object/equals/), requiere que las sobrescrituras cumplan los requisitos de un operador de equivalencia. Por lo tanto, System.Double.Equals y System.Single.Equals devuelven True al comparar dos NaNs, mientras que el operador de igualdad devuelve False en ese caso, según lo requerido por el estándar.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const **float**\& | El primer comparando |
| b | const **float**\& | El segundo comparando |

### Valor de retorno

True si ambos valores son NaN o son iguales, de lo contrario - false

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)