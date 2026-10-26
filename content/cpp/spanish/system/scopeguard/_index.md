---
title: ScopeGuard
second_title: Referencia de la API de Aspose.Slides para C++
description: La clase de servicio que proporciona servicios para ejecutar un objeto de función específico cuando una instancia de la clase sale del alcance.
type: docs
weight: 1886
url: /es/system/scopeguard/
---
## ScopeGuard estructura


La clase de servicio que proporciona servicios para ejecutar un objeto de función específico cuando una instancia de la clase sale del alcance.

```cpp
template<typename F>class ScopeGuard
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| F | El tipo del objeto de función invocado por las instancias de la clase ScopedGuard |
## Métodos

| Método | Descripción |
| --- | --- |
| void [Disable](./disable/)() | Desactiva la invocación del guardia. |
| [ScopeGuard](./scopeguard/)(F) | Construye una instancia configurada para invocar el objeto de función especificado. |
| [~ScopeGuard](./~scopeguard/)() | Invoca el objeto de función pasado al constructor. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)