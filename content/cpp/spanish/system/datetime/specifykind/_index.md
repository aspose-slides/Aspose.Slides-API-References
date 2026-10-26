---
title: SpecifyKind()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un nuevo objeto DateTime que representa el mismo número de ticks que el objeto DateTime especificado y representa la hora local, la hora UTC o ninguno, según lo especificado por el argumento kind.
type: docs
weight: 833
url: /es/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) método


Construye un nuevo objeto [DateTime](../) que representa el mismo número de ticks que el objeto [DateTime](../) especificado y representa la hora local, la hora UTC o ninguno, según lo especificado por el argumento **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DateTime](../) | El objeto [DateTime](../) del que copiar el número de ticks |
| kind | [DateTimeKind](../../datetimekind/) | Especifica si el nuevo objeto debe representar la hora local, la hora UTC o ninguno. |

### Valor de retorno

Un nuevo objeto [DateTime](../) que representa el mismo número de ticks que **value** y el valor DateTimeKind especificado por **kind**.

## Ver también

* Enum [DateTimeKind](../../datetimekind/)
* Clase [DateTime](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)