---
title: operator!=()
second_title: Referencia de API de Aspose.Slides para C++
description: Operador de comparación de desigualdad.
type: docs
weight: 313
url: /es/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const método

Operador de comparación de desigualdad.

```cpp
bool System::String::operator!=(const String &str) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para comparar con el actual. |

### Valor de retorno

false si ambas cadenas son nulas o ambas no son nulas y coinciden, true en caso contrario.

## String::operator!=(std::nullptr_t) const método

Comprueba si la cadena no es nula. Aplica la misma lógica que la llamada a [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### Valor de retorno

false si la cadena es nula, true en caso contrario.

## Ver también

* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)