---
title: WaitOne()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda o manipulador disparar por período ilimitado.
type: docs
weight: 27
url: /pt/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() método


Aguarda o manipulador disparar por período ilimitado.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### Valor de retorno

Sempre retorna true, pois nenhum tempo limite ocorre.

## WaitHandle::WaitOne(int) método


Aguarda o manipulador disparar.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) para aguardar, em milissegundos; -1 significa espera infinita, 0 significa verificação e retorno, valores positivos são tempos limite. |

### Valor de retorno

True se o manipulador disparou, false se o tempo limite foi excedido.

## WaitHandle::WaitOne(TimeSpan) método


Aguarda o manipulador disparar.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Um [System::TimeSpan](../../../system/timespan/) que representa o número de milissegundos a aguardar, ou um [System::TimeSpan](../../../system/timespan/) que representa -1 milissegundos para aguardar indefinidamente. |

### Valor de retorno

True se o manipulador disparou, false se o tempo limite foi excedido.

## WaitHandle::WaitOne(int, bool) método


Aguarda o manipulador disparar.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) para aguardar, em milissegundos; -1 significa espera infinita, 0 significa verificação e retorno, valores positivos são tempos limite. |
| exitContext | **bool** | Se true, a espera deve liberar o bloqueio no manipulador antes de aguardá-lo. |

### Valor de retorno

True se o manipulador disparou, false se o tempo limite foi excedido.

## Veja também

* Classe [WaitHandle](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espaço de nomes [System::Threading](../../)
* Library [Aspose.Slides](../../../)