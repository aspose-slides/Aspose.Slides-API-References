---
title: TryEnter()
second_title: Referência da API Aspose.Slides for C++
description: Tenta adquirir um bloqueio exclusivo no objeto especificado Não implementado.
type: docs
weight: 27
url: /pt/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) método

Tenta adquirir um bloqueio exclusivo no objeto especificado Não implementado.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) método

Tenta adquirir um bloqueio exclusivo no objeto especificado e define atomicamente um valor que indica se o bloqueio foi obtido.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) método

Tenta, pelo número especificado de milissegundos, adquirir um bloqueio exclusivo no objeto especificado Não implementado.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) método

Tenta, pelo período de tempo especificado, adquirir um bloqueio exclusivo no objeto especificado Não implementado.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) método

Tenta, pelo período de tempo especificado, adquirir um bloqueio exclusivo no objeto especificado e define atomicamente um valor que indica se o bloqueio foi obtido.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) método

Tenta, pelo período de tempo especificado, adquirir um bloqueio exclusivo no objeto especificado e define atomicamente um valor que indica se o bloqueio foi obtido.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Monitor](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espaço de nomes [System::Threading](../../)
* Library [Aspose.Slides](../../../)