---
title: operator==()
second_title: Referencia de API de Aspose.Slides para C++
description: Operador de igualdad para ResultValueTask.
type: docs
weight: 131
url: /es/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const método

Operador de igualdad para [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | El otro [ResultValueTask](../) para comparar con esta instancia. |

### Valor devuelto

bool True si ambas tareas tienen el mismo valor de resultado o hacen referencia a la misma tarea subyacente; de lo contrario, false.

## Observaciones

Si alguna de las instancias contiene un valor de resultado directo, compara los resultados directamente. De lo contrario, compara los punteros de la tarea subyacente. 

## Ver también

* Clase [ResultValueTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)