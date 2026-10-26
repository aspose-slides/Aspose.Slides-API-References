---
title: WaitOne()
second_title: Referencia de API de Aspose.Slides para C++
description: Bloquea el mutex. Realiza una espera ilimitada si es necesario.
type: docs
weight: 53
url: /es/system.threading/mutex/waitone/
---
## Mutex::WaitOne() método

Bloquea el mutex. Realiza una espera ilimitada si es necesario.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Valor devuelto

Siempre devuelve true ya que no devuelve hasta que el mutex está bloqueado.

## Mutex::WaitOne(int) método

Bloquea el mutex. Realiza una espera si es necesario.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsTimeout | int | Tiempo de espera en milisegundos. |

### Valor devuelto

Devuelve true si el mutex fue bloqueado o false si se superó el tiempo de espera.

## Mutex::WaitOne(TimeSpan) método

Bloquea el mutex. Realiza una espera si es necesario.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) que representa el número de milisegundos a esperar, o un [System::TimeSpan](../../../system/timespan/) que representa -1 milisegundos para esperar indefinidamente. |

### Valor devuelto

Devuelve true si el mutex fue bloqueado o false si se superó el tiempo de espera.

## Ver también

* Clase [Mutex](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)