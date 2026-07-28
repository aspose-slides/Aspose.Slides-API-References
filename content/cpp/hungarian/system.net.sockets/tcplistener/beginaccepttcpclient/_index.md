---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides C++ API hivatkozás
description: Aszinkron elfogadási műveletet indít el.
type: docs
weight: 170
url: /hu/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) metódus

Aszinkron elfogadási műveletet indít el.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Az a visszahívás, amely akkor lesz meghívva, amikor a művelet befejeződik. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által megadott adatok, amelyeket az egyes aszinkron kapcsolódási műveletek egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron elfogadási műveletet képviseli.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [TcpListener](../)
* Névtér [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)