---
title: WaitAny()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que qualquer um dos manipuladores dispare.
type: docs
weight: 14
url: /pt/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) método


Aguarda até que qualquer um dos manipuladores dispare.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manipuladores a serem aguardados. |
| millisecondsTimeout | int | [Timeout](../../timeout/) a esperar, em milissegundos; -1 significa espera infinita, 0 significa verificação e retorno, valores positivos são tempos limite. |

### Valor de Retorno

True se algum handle disparou, false se o tempo limite foi excedido.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) método


Aguarda até que qualquer um dos manipuladores dispare.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manipuladores a serem aguardados. |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) que representa o número de milissegundos a esperar, ou um [System::TimeSpan](../../../system/timespan/) que representa -1 milissegundos para espera indefinida. |

### Valor de Retorno

True se algum handle disparou, false se o tempo limite foi excedido.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) método


Aguarda até que qualquer um dos manipuladores dispare.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manipuladores a serem aguardados. |

### Valor de Retorno

True quando todo elemento em waitHandles recebeu um sinal; caso contrário o método nunca retorna.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WaitHandle](../)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)