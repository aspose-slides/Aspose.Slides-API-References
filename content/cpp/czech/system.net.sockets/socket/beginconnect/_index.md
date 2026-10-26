---
title: BeginConnect()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zahajuje asynchronní operaci připojení.
type: docs
weight: 573
url: /cs/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) metoda


Zahajuje asynchronní operaci připojení.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které bude zavoláno po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data použité k jedinečné identifikaci každé asynchronní operace připojení. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci připojení.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda


Zahajuje asynchronní operaci připojení.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Název vzdáleného hostitele. |
| port | **int32_t** | Číslo portu vzdáleného hostitele. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které bude zavoláno po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data použité k jedinečné identifikaci každé asynchronní operace připojení. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci připojení.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda


Zahajuje asynchronní operaci připojení.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | IP adresa vzdáleného hostitele. |
| port | **int32_t** | Číslo portu vzdáleného hostitele. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které bude zavoláno po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data použité k jedinečné identifikaci každé asynchronní operace připojení. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci připojení.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda


Zahajuje asynchronní operaci připojení.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP adresy vzdáleného hostitele. |
| port | **int32_t** | Číslo portu vzdáleného hostitele. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které bude zavoláno po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data použité k jedinečné identifikaci každé asynchronní operace připojení. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci připojení.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [EndPoint](../../../system.net/endpoint/)
* Třída [Object](../../../system/object/)
* Třída [Socket](../)
* Třída [String](../../../system/string/)
* Třída [IPAddress](../../../system.net/ipaddress/)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)