---
title: TimerQueue
second_title: Referencia de API de Aspose.Slides para C++
description: Cola que maneja objetos Timer. Esto es sólo una implementación. Los objetos Timer se registran allí por sí mismos, no tienes que hacerlo para usarlos - usa la API de la clase Timer en su lugar. Este es un tipo singleton con gestión de memoria realizada por función(es) de acceso. Nunca deberías crear instancias de él directamente.
type: docs
weight: 261
url: /es/system.threading/timerqueue/
---
## TimerQueue clase

Cola que maneja objetos [Timer](../timer/). Esto es sólo una implementación. [Timer](../timer/) objetos se registran allí por sí mismos, no tienes que hacerlo para usarlos - usa la API de la clase [Timer](../timer/) en su lugar. Este es un tipo singleton con gestión de memoria realizada por función(es) de acceso. Nunca deberías crear instancias de él directamente.

```cpp
class TimerQueue
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Registra el temporizador en la cola. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Elimina el temporizador de la cola. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Singleton de implementación. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Une el hilo de trabajo. Espera indefinidamente si es necesario. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Sin copia. |
| [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Sin copia. |

## Ver también

* Espacio de nombres [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)