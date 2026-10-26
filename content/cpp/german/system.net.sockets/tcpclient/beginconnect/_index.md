---
title: BeginConnect()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet eine asynchrone Verbindungsoperation.
type: docs
weight: 261
url: /de/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet eine asynchrone Verbindungsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | [String](../../../system/string/) | Ein Remote-Host-Name. |
| port | **int32_t** | Ein Port des Remote-Hosts. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Rückruf, der aufgerufen wird, wenn die Operation abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Benutzerbereitgestellte Daten, die verwendet werden, um jede asynchrone Verbindungsoperation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die initiierte asynchrone Verbindungsoperation darstellt.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet eine asynchrone Verbindungsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Die IP-Adresse eines Remote-Hosts. |
| port | **int32_t** | Ein Port des Remote-Hosts. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Rückruf, der aufgerufen wird, wenn die Operation abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Benutzerbereitgestellte Daten, die verwendet werden, um jede asynchrone Verbindungsoperation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die initiierte asynchrone Verbindungsoperation darstellt.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet eine asynchrone Verbindungsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Die IP-Adressen eines Remote-Hosts. |
| port | **int32_t** | Ein Port des Remote-Hosts. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Rückruf, der aufgerufen wird, wenn die Operation abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Benutzerbereitgestellte Daten, die verwendet werden, um jede asynchrone Verbindungsoperation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die initiierte asynchrone Verbindungsoperation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Klasse [TcpClient](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)