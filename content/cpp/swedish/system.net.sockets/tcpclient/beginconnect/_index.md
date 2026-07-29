---
title: BeginConnect()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron anslutningsoperation.
type: docs
weight: 261
url: /sv/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | [String](../../../system/string/) | Ett fjärrvärdsnamn. |
| port | **int32_t** | En port för fjärrvärden. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En callback som kommer att anropas när operationen är klar. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona anslutningsoperationen.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | IP-adressen för en fjärrvärd. |
| port | **int32_t** | En port för fjärrvärden. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En callback som kommer att anropas när operationen är klar. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona anslutningsoperationen.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP-adresserna för en fjärrvärd. |
| port | **int32_t** | En port för fjärrvärden. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | En callback som kommer att anropas när operationen är klar. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona anslutningsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [TcpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)