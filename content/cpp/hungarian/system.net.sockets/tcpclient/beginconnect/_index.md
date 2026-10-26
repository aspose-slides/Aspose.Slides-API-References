---
title: BeginConnect()
second_title: Aspose.Slides C++ API referenciája
description: Elindít egy aszinkron csatlakozási műveletet.
type: docs
weight: 261
url: /hu/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Elindít egy aszinkron csatlakozási műveletet.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | [String](../../../system/string/) | Egy távoli gép neve. |
| port | **int32_t** | A távoli gép portja. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor lesz meghívva. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által biztosított adat, amelyet minden aszinkron csatlakozási művelet egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron csatlakozási műveletet képviseli.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Elindít egy aszinkron csatlakozási műveletet.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | A távoli gép IP-címe. |
| port | **int32_t** | A távoli gép portja. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor lesz meghívva. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által biztosított adat, amelyet minden aszinkron csatlakozási művelet egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron csatlakozási műveletet képviseli.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Elindít egy aszinkron csatlakozási műveletet.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | A távoli gép IP-címei. |
| port | **int32_t** | A távoli gép portja. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor lesz meghívva. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által biztosított adat, amelyet minden aszinkron csatlakozási művelet egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron csatlakozási műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [String](../../../system/string/)
* Osztály [Object](../../../system/object/)
* Osztály [TcpClient](../)
* Osztály [IPAddress](../../../system.net/ipaddress/)
* Névtér [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)