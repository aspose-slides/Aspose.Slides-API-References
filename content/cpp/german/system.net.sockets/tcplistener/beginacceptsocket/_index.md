---
title: BeginAcceptSocket()
second_title: Aspose.Slides für C++ API-Referenz
description: Initiiert einen asynchronen Akzeptvorgang.
type: docs
weight: 144
url: /de/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) Methode


Initiiert einen asynchronen Akzeptvorgang.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, das aufgerufen wird, wenn der Vorgang abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die jede asynchrone Verbindungsoperation eindeutig identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das den initiierten asynchronen Akzeptvorgang darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [TcpListener](../)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)