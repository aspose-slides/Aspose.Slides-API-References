---
title: BeginAcceptSocket()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zahajuje asynchronní operaci přijetí.
type: docs
weight: 144
url: /cs/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) metoda

Zahajuje asynchronní operaci přijetí.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Zpětná volání, která bude zavolána po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jednoznačnému identifikování každé asynchronní operace připojení. |

### Návratová hodnota

[IAsyncResult](../../../system/iasyncresult/) objekt představující zahájenou asynchronní operaci přijetí.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [TcpListener](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)