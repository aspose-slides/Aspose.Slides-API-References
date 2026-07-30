---
title: TryEnter()
second_title: Riferimento API di Aspose.Slides per C++
description: Tentativo di acquisire un lock esclusivo sull'oggetto specificato Non implementato.
type: docs
weight: 27
url: /it/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) metodo

Tentativo di acquisire un lock esclusivo sull'oggetto specificato Non implementato.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) metodo

Tentativo di acquisire un lock esclusivo sull'oggetto specificato e impostare in modo atomico un valore che indica se il lock è stato acquisito.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) metodo

Tentativi, per il numero specificato di millisecondi, di acquisire un lock esclusivo sull'oggetto specificato Non implementato.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) metodo


Tentativi, per l'intervallo di tempo specificato, di acquisire un lock esclusivo sull'oggetto specificato Non implementato.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) metodo


Tentativi, per l'intervallo di tempo specificato, di acquisire un lock esclusivo sull'oggetto specificato e impostare in modo atomico un valore che indica se il lock è stato acquisito.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) metodo


Tentativi, per l'intervallo di tempo specificato, di acquisire un lock esclusivo sull'oggetto specificato e impostare in modo atomico un valore che indica se il lock è stato acquisito.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Monitor](../)
* Classe [TimeSpan](../../../system/timespan/)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)