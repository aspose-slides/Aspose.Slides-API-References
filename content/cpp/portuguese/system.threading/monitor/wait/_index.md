---
title: Wait()
second_title: Referência da API Aspose.Slides para C++
description: Libera o bloqueio em um objeto e bloqueia a thread atual até que recupere o bloqueio. Se o intervalo de tempo limite especificado expirar, a thread entra na fila de prontas. Opcionalmente sai do domínio de sincronização para o contexto sincronizado antes da espera e recupera o domínio depois. Não implementado.
type: docs
weight: 53
url: /pt/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) método


Libera o bloqueio em um objeto e bloqueia a thread atual até que recupere o bloqueio. Se o intervalo de tempo limite especificado expirar, a thread entra na fila de prontas. Opcionalmente sai do domínio de sincronização para o contexto sincronizado antes da espera e recupera o domínio depois. Não implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) método


Libera o bloqueio em um objeto e bloqueia a thread atual até que recupere o bloqueio. Se o intervalo de tempo limite especificado expirar, a thread entra na fila de prontas. Opcionalmente sai do domínio de sincronização para o contexto sincronizado antes da espera e recupera o domínio depois. Não implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) método


Libera o bloqueio em um objeto e bloqueia a thread atual até que recupere o bloqueio. Se o intervalo de tempo limite especificado expirar, a thread entra na fila de prontas. Não implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) método


Libera o bloqueio em um objeto e bloqueia a thread atual até que recupere o bloqueio. Se o intervalo de tempo limite especificado expirar, a thread entra na fila de prontas. Não implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&) método


Libera o bloqueio em um objeto e bloqueia a thread atual até que recupere o bloqueio Não implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```


## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Monitor](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espaço de nomes [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)