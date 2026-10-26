---
title: BeginConnect()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron anslutningsoperation.
type: docs
weight: 573
url: /sv/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) metod


Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |
| callback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som kommer att anropas när operationen slutförs. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona anslutningsoperationen.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod


Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | [String](../../../system/string/) | Fjärrvärdens namn. |
| port | **int32_t** | Portnumret för fjärrvärden. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som kommer att anropas när operationen slutförs. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona anslutningsoperationen.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod


Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Den fjärrvärdens IP-adress. |
| port | **int32_t** | Portnumret för fjärrvärden. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som kommer att anropas när operationen slutförs. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona anslutningsoperationen.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod


Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP-adresserna för fjärrvärden. |
| port | **int32_t** | Portnumret för fjärrvärden. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som kommer att anropas när operationen slutförs. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona anslutningsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [EndPoint](../../../system.net/endpoint/)
* Klass [Object](../../../system/object/)
* Klass [Socket](../)
* Klass [String](../../../system/string/)
* Klass [IPAddress](../../../system.net/ipaddress/)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)