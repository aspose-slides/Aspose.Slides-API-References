---
title: MakeScopeGuard()
second_title: Referencia de la API de Aspose.Slides para C++
description: Una función de fábrica que crea instancias de la clase ScopedGuard.
type: docs
weight: 2809
url: /es/system/makescopeguard/
---
## System::MakeScopeGuard(F) función

Una función de fábrica que crea instancias de la clase ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| El | tipo del objeto función que será invocado por el objeto ScopedGuard construido |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | F | El objeto función que se pasa al constructor de la clase ScopedGuard. |

### Valor devuelto

Una nueva instancia de la clase ScopedGuard

## Ver también

* Struct [ScopeGuard](../scopeguard/)
* Espacio de nombres [System](../)
* Library [Aspose.Slides](../../)