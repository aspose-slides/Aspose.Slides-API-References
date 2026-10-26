---
title: Wait()
second_title: Riferimento API di Aspose.Slides per C++
description: Rilascia il lock su un oggetto e blocca il thread corrente fino a riacquisire il lock. Se l'intervallo di timeout specificato scade, il thread entra nella coda pronta. Facoltativamente esce dal dominio di sincronizzazione per il contesto sincronizzato prima dell'attesa e riacquista il dominio successivamente. Non implementato.
type: docs
weight: 53
url: /it/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) metodo

Rilascia il lock su un oggetto e blocca il thread corrente fino a riacquisire il lock. Se l'intervallo di timeout specificato scade, il thread entra nella coda pronta. Facoltativamente esce dal dominio di sincronizzazione per il contesto sincronizzato prima dell'attesa e riacquista il dominio successivamente. Non implementato.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) metodo

Rilascia il lock su un oggetto e blocca il thread corrente fino a riacquisire il lock. Se l'intervallo di timeout specificato scade, il thread entra nella coda pronta. Facoltativamente esce dal dominio di sincronizzazione per il contesto sincronizzato prima dell'attesa e riacquista il dominio successivamente. Non implementato.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) metodo

Rilascia il lock su un oggetto e blocca il thread corrente fino a riacquisire il lock. Se l'intervallo di timeout specificato scade, il thread entra nella coda pronta. Non implementato.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) metodo

Rilascia il lock su un oggetto e blocca il thread corrente fino a riacquisire il lock. Se l'intervallo di timeout specificato scade, il thread entra nella coda pronta. Non implementato.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) metodo

Rilascia il lock su un oggetto e blocca il thread corrente fino a riacquisire il lock Non implementato.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Monitor](../)
* Classe [TimeSpan](../../../system/timespan/)
* Spazio dei nomi [System::Threading](../../)
* Library [Aspose.Slides](../../../)