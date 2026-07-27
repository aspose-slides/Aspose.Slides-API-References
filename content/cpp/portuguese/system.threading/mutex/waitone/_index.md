---
title: WaitOne()
second_title: Referência da API Aspose.Slides para C++
description: Bloqueia o mutex. Executa espera ilimitada, se necessário.
type: docs
weight: 53
url: /pt/system.threading/mutex/waitone/
---
## Mutex::WaitOne() método


Bloqueia o mutex. Executa espera ilimitada, se necessário.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### Valor de Retorno

Sempre retorna true, pois não retorna até que o mutex esteja bloqueado.

## Mutex::WaitOne(int) método


Bloqueia o mutex. Executa espera, se necessário.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Tempo limite de espera em milissegundos. |

### Valor de Retorno

Retorna true se o mutex foi bloqueado ou false se o tempo limite for excedido.

## Mutex::WaitOne(TimeSpan) método


Bloqueia o mutex. Executa espera, se necessário.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Um [System::TimeSpan](../../../system/timespan/) que representa o número de milissegundos a esperar, ou um [System::TimeSpan](../../../system/timespan/) que representa -1 milissegundos para esperar indefinidamente. |

### Valor de Retorno

Retorna true se o mutex foi bloqueado ou false se o tempo limite for excedido.

## Veja Também

* Classe [Mutex](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espaço de nomes [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)