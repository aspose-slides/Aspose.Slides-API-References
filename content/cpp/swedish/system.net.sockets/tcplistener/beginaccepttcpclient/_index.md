---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron acceptoperation.
type: docs
weight: 170
url: /sv/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron acceptoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | En återanropning som kommer att anropas när operationen är klar. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användardata som används för att unikt identifiera varje asynkron anslutningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/) objekt som representerar den initierade asynkrona acceptoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [TcpListener](../)
* Namnrymd [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)