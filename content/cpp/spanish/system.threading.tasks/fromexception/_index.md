---
title: FromException()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una tarea que se ha completado con una excepción especificada.
type: docs
weight: 131
url: /es/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) función


Crea una tarea que se ha completado con una excepción especificada.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | La excepción con la que se completa la tarea. |

### Valor de retorno

Una tarea con error.

## System::Threading::Tasks::FromException(const Exception\&) función


Crea una tarea que se ha completado con una excepción especificada y un tipo de resultado.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TResult | El tipo del resultado de la tarea. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | La excepción con la que se completa la tarea. |

### Valor de retorno

Una tarea con error con el tipo de resultado especificado.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)