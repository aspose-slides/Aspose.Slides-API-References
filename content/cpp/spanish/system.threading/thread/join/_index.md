---
title: Join()
second_title: Referencia de la API de Aspose.Slides para C++
description: Une el hilo administrado. Realiza una espera ilimitada si es necesario.
type: docs
weight: 196
url: /es/system.threading/thread/join/
---
## Thread::Join() método


Une el hilo administrado. Realiza una espera ilimitada si es necesario.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) método


Une el hilo administrado. Realiza una espera limitada.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsTimeout | int | Tiempo de espera en milisegundos. |

### Valor devuelto

True si el hilo se unió correctamente, false si se excedió el tiempo de espera.

## Thread::Join(TimeSpan) método


Une el hilo administrado. Realiza una espera limitada.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [TimeSpan](../../../system/timespan/) configurado al tiempo que se debe esperar a que el hilo termine. |

### Valor devuelto

True si el hilo se unió correctamente, false si se excedió el tiempo de espera.

## Ver también

* Clase [Thread](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)