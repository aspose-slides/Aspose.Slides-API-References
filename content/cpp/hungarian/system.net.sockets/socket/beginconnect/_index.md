---
title: BeginConnect()
second_title: Aspose.Slides C++ API Referencia
description: Aszinkron csatlakozási műveletet indít el.
type: docs
weight: 573
url: /hu/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) metódus


Aszinkron csatlakozási műveletet indít el.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor lesz meghívva. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adat, amely egyértelműen azonosítja az egyes aszinkron csatlakozási műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a elindított aszinkron csatlakozási műveletet képviseli.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metódus


Aszinkron csatlakozási műveletet indít el.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | [String](../../../system/string/) | A távoli gép neve. |
| port | **int32_t** | A távoli gép portszáma. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor lesz meghívva. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adat, amely egyértelműen azonosítja az egyes aszinkron csatlakozási műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a elindított aszinkron csatlakozási műveletet képviseli.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metódus


Aszinkron csatlakozási műveletet indít el.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | A távoli gép IP-címe. |
| port | **int32_t** | A távoli gép portszáma. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor lesz meghívva. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adat, amely egyértelműen azonosítja az egyes aszinkron csatlakozási műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a elindított aszinkron csatlakozási műveletet képviseli.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metódus


Aszinkron csatlakozási műveletet indít el.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | A távoli gép IP-címei. |
| port | **int32_t** | A távoli gép portszáma. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor lesz meghívva. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adat, amely egyértelműen azonosítja az egyes aszinkron csatlakozási műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a elindított aszinkron csatlakozási műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [EndPoint](../../../system.net/endpoint/)
* Osztály [Object](../../../system/object/)
* Osztály [Socket](../)
* Osztály [String](../../../system/string/)
* Osztály [IPAddress](../../../system.net/ipaddress/)
* Névtere [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)