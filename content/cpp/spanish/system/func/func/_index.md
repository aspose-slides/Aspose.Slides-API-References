---
title: Func()
second_title: Referencia de API de Aspose.Slides para C++
description: Constructor predeterminado que crea null-Func.
type: docs
weight: 1
url: /es/system/func/func/
---
## Func::Func() constructor

Constructor predeterminado que crea null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) constructor

Constructor que construye el objeto [Func](../) y asigna un valor (ya sea una callback real o nullptr) a él.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de argumento. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg | T\&& | Argumento. |

## Func::Func(const Func\&) constructor

Constructor de copia.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) para copiar datos de. |

## Func::Func(Func\&&) constructor

Constructor de movimiento.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) para mover datos de. |

## Ver también

* Clase [Func](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)