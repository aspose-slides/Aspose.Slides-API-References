---
title: QueueUserWorkItem()
second_title: Referência da API Aspose.Slides para C++
description: Insere o item de trabalho na fila que está presente com um callback sem parâmetro.
type: docs
weight: 14
url: /pt/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) método


Coloca o item de trabalho na fila que está presente com um callback sem parâmetro.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Função de callback a ser usada como tarefa. |

### Valor de Retorno

Sempre retorna true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) método


Coloca o item de trabalho na fila que está presente com um callback sem parâmetro.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Função de callback a ser usada como tarefa. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Parâmetro da função de tarefa. |

### Valor de Retorno

Sempre retorna true.

## Veja Também

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ThreadPool](../)
* Class [Object](../../../system/object/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)