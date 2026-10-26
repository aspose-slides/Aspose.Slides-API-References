---
title: Timer()
second_title: Referencia de la API de Aspose.Slides para C++
description: Constructor.
type: docs
weight: 1
url: /es/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor

Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Función que será llamada por el temporizador. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor

Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Función que será llamada por el temporizador. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argumento de la función de devolución de llamada. |
| dueTime | **int64_t** | [Timeout](../../timeout/) antes de la primera invocación de la función de devolución de llamada, en milisegundos; los valores negativos no programan el temporizador después de la creación, por lo que puede volver a programarse más tarde. |
| period | **int64_t** | [Timeout](../../timeout/) entre invocaciones consecutivas de la función de devolución de llamada, en milisegundos; los valores no positivos indican que el temporizador debe ejecutarse solo una vez. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor

Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Función que será llamada por el temporizador. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argumento de la función de devolución de llamada. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) antes de la primera invocación de la función de devolución de llamada; los valores negativos no programan el temporizador después de la creación, por lo que puede volver a programarse más tarde. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) entre invocaciones consecutivas de la función de devolución de llamada; los valores no positivos indican que el temporizador debe ejecutarse solo una vez. |

## Ver también

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Timer](../)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)