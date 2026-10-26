---
title: BeginGetHostAddresses()
second_title: Referência da API Aspose.Slides for C++
description: Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando a string especificada que contém um nome de host ou endereço IP.
type: docs
weight: 131
url: /pt/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando a string especificada que contém um nome de host ou endereço IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Uma string que contém um nome de host ou endereço IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar unicamente cada operação assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [String](../../../system/string/)
* Classe [Object](../../../system/object/)
* Classe [Dns](../)
* Namespace [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)