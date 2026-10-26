---
title: TryEnter()
second_title: Referencia de API de Aspose.Slides para C++
description: Intenta adquirir un bloqueo exclusivo en el objeto especificado No implementado.
type: docs
weight: 27
url: /es/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) método


Intenta adquirir un bloqueo exclusivo en el objeto especificado No implementado.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) método


Intenta adquirir un bloqueo exclusivo en el objeto especificado y establece de forma atómica un valor que indica si el bloqueo fue tomado.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) método


Intenta, durante el número especificado de milisegundos, adquirir un bloqueo exclusivo en el objeto especificado No implementado.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) método


Intenta, durante el período especificado, adquirir un bloqueo exclusivo en el objeto especificado No implementado.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) método


Intenta, durante el período especificado, adquirir un bloqueo exclusivo en el objeto especificado y establece de forma atómica un valor que indica si el bloqueo fue tomado.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) método


Intenta, durante el período especificado, adquirir un bloqueo exclusivo en el objeto especificado y establece de forma atómica un valor que indica si el bloqueo fue tomado.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [Monitor](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)