---
title: BeginGetHostByName()
second_title: Aspose.Slides para C++ Referência da API
description: Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando o nome de host especificado.
type: docs
weight: 53
url: /pt/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando o nome de host especificado.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Um nome de host. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar exclusivamente cada operação assíncrona. |

### Valor de Retorno

Um [IAsyncResult](../../../system/iasyncresult/) objeto representando a operação assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)