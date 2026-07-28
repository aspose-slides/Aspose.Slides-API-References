---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Inicjuje asynchroniczną operację akceptacji.
type: docs
weight: 170
url: /pl/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczną operację akceptacji.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Funkcja zwrotna, która zostanie wywołana po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika służące do jednoznacznego identyfikowania każdej asynchronicznej operacji połączenia. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację akceptacji.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [TcpListener](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)