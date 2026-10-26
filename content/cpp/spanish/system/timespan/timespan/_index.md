---
title: TimeSpan()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un objeto TimeSpan que representa un intervalo de tiempo cero.
type: docs
weight: 1
url: /es/system/timespan/timespan/
---
## TimeSpan::TimeSpan() constructor


Construye un objeto [TimeSpan](../) que representa un intervalo de tiempo cero.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) constructor


Construye una instancia de la clase [TimeSpan](../) que representa el intervalo de tiempo especificado.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ticks | **int64_t** | El intervalo de tiempo que será representado por la instancia que se está construyendo, expresado como el número de intervalos de 100 nanosegundos. |

## TimeSpan::TimeSpan(int, int, int) constructor


Construye una instancia de la clase [TimeSpan](../) que representa el intervalo de tiempo que es igual a la suma de la cantidad especificada de horas, minutos y segundos.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hours | int | El número de horas en el componente de horas del intervalo de tiempo que será representado por la instancia que se está construyendo |
| minutes | int | El número de minutos en el componente de minutos del intervalo de tiempo que será representado por la instancia que se está construyendo |
| seconds | int | El número de segundos en el componente de segundos del intervalo de tiempo que será representado por la instancia que se está construyendo |

## TimeSpan::TimeSpan(int, int, int, int, int) constructor


Construye una instancia de la clase [TimeSpan](../) que representa el intervalo de tiempo que es igual a la suma de la cantidad especificada de horas, minutos, segundos y milisegundos.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| days | int | El número de días en el componente de días del intervalo de tiempo que será representado por la instancia que se está construyendo |
| hours | int | El número de horas en el componente de horas del intervalo de tiempo que será representado por la instancia que se está construyendo |
| minutes | int | El número de minutos en el componente de minutos del intervalo de tiempo que será representado por la instancia que se está construyendo |
| seconds | int | El número de segundos en el componente de segundos del intervalo de tiempo que será representado por la instancia que se está construyendo |
| milliseconds | int | El número de milisegundos en el componente de milisegundos del intervalo de tiempo que será representado por la instancia que se está construyendo |

## TimeSpan::TimeSpan(const TimeSpan\&) constructor


Construye un objeto [TimeSpan](../) que representa el intervalo de tiempo igual al intervalo de tiempo representado por el objeto [TimeSpan](../) especificado.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Ver también

* Clase [TimeSpan](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)