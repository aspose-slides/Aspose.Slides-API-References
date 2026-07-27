---
title: QueueUserWorkItem()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona item de trabalho à fila.
type: docs
weight: 1
url: /pt/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) método

Adiciona item de trabalho à fila.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to execute. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Callback function argument. |

### Valor de Retorno

Sempre retorna verdadeiro.

## Veja Também

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ThreadPoolImpl](../)
* Espaço de nomes [System::Threading](../../)
* Library [Aspose.Slides](../../../)