---
title: BeginResolve()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando o nome do host especificado.
type: docs
weight: 157
url: /pt/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando o nome de host especificado.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Um nome de host que é usado para criar uma nova instância da [IPHostEntry](../../iphostentry/) classe. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Um retorno de chamada a ser invocado quando a operação for concluída. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação assíncrona. |

### Valor de Retorno

Um [IAsyncResult](../../../system/iasyncresult/) objeto que representa a operação assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [String](../../../system/string/)
* Classe [Object](../../../system/object/)
* Classe [Dns](../)
* Namespace [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)