---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides per C++ Riferimento API
description: Avvia un'operazione di accettazione asincrona.
type: docs
weight: 170
url: /it/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione di accettazione asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback che verrà chiamata al completamento dell'operazione. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente utilizzati per identificare in modo univoco ogni operazione di connessione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di accettazione asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [TcpListener](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)