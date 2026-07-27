---
title: BeginAcceptSocket()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação de aceitação assíncrona.
type: docs
weight: 144
url: /pt/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma operação de aceitação assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Um callback que será chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação de conexão assíncrona. |

### Valor de retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de aceitação assíncrona iniciada.

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [TcpListener](../)
* Espaço de nomes [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)