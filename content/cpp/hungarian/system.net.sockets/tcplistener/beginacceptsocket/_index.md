---
title: BeginAcceptSocket()
second_title: Aspose.Slides C++ API referenciája
description: Elindít egy aszinkron elfogadási műveletet.
type: docs
weight: 144
url: /hu/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) method

Elindít egy aszinkron elfogadási műveletet.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor lesz meghívva. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adat, amelyet minden aszinkron csatlakozási művelet egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron elfogadási műveletet reprezentálja.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [TcpListener](../)
* Névtér [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)