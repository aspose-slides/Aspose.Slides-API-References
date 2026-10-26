---
title: WaitOne()
second_title: Referencia de API de Aspose.Slides para C++
description: Bloquea el semáforo. Realiza una espera ilimitada si es necesario.
type: docs
weight: 40
url: /es/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() método


Bloquea el semáforo. Realiza una espera ilimitada si es necesario.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Valor devuelto

Siempre devuelve true ya que no regresa hasta que el semáforo esté bloqueado.

## Semaphore::WaitOne(int) método


Bloquea el semáforo. Realiza una espera si es necesario.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsTimeout | int | Tiempo de espera en milisegundos. |

### Valor devuelto

Devuelve true si el semáforo fue bloqueado o false si se superó el tiempo de espera.

## Ver también

* Clase [Semaphore](../)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)