---
title: Semaphore()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un semáforo sin nombre.
type: docs
weight: 1
url: /es/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) constructor

Crea un semáforo sin nombre.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| initialCount | int | Conteo inicial de entradas activas. |
| maximumCount | int | Conteo máximo de entradas permitidas. |

## Semaphore::Semaphore(int, int, const String\&) constructor

Crea un semáforo con nombre.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| initialCount | int | Conteo inicial de entradas activas. |
| maximumCount | int | Conteo máximo de entradas permitidas. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nombre. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) constructor

Crea un semáforo con nombre.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| initialCount | int | Conteo inicial de entradas activas. |
| maximumCount | int | Conteo máximo de entradas permitidas. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nombre. |
| createdNew | **bool**\& | Referencia a una variable que se establece en true si el semáforo se creó y en false si se reutilizó uno existente con el mismo nombre |

## Ver también

* Clase [Semaphore](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)