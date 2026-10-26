---
title: WaitAll()
second_title: Aspose.Slides para Referência da API C++
description: Aguarda até que todos os manipuladores sejam disparados.
type: docs
weight: 1
url: /pt/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) método


Aguarda até que todos os manipuladores sejam disparados.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manipuladores a aguardar. |
| millisecondsTimeout | int | [Timeout](../../timeout/) para aguardar, em milissegundos; -1 significa espera infinita, 0 significa checar e retornar, valores positivos são tempos limite. |

### Valor de Retorno

True se todos os manipuladores foram disparados, false se o tempo limite foi excedido.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) método


Aguarda até que todos os manipuladores sejam disparados.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manipuladores a aguardar. |
| timeout | [TimeSpan](../../../system/timespan/) | Um [System::TimeSpan](../../../system/timespan/) que representa o número de milissegundos para aguardar, ou um [System::TimeSpan](../../../system/timespan/) que representa -1 milissegundos para aguardar indefinidamente. |

### Valor de Retorno

True se todos os manipuladores foram disparados, false se o tempo limite foi excedido.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) método


Aguarda até que todos os manipuladores sejam disparados.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manipuladores a aguardar. |

### Valor de Retorno

True quando cada elemento em waitHandles recebeu um sinal; caso contrário o método nunca retorna.

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WaitHandle](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espaço de nomes [System::Threading](../../)
* Library [Aspose.Slides](../../../)