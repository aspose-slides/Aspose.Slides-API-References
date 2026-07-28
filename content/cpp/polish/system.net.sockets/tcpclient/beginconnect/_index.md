---
title: BeginConnect()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Inicjuje asynchroniczną operację połączenia.
type: docs
weight: 261
url: /pl/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda


Inicjuje asynchroniczną operację połączenia.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nazwa zdalnego hosta. |
| port | **int32_t** | Port zdalnego hosta. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika, używane do jednoznacznej identyfikacji każdej asynchronicznej operacji połączenia. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację połączenia.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda


Inicjuje asynchroniczną operację połączenia.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Adres IP zdalnego hosta. |
| port | **int32_t** | Port zdalnego hosta. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika, używane do jednoznacznej identyfikacji każdej asynchronicznej operacji połączenia. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację połączenia.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda


Inicjuje asynchroniczną operację połączenia.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Adresy IP zdalnego hosta. |
| port | **int32_t** | Port zdalnego hosta. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika, używane do jednoznacznej identyfikacji każdej asynchronicznej operacji połączenia. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację połączenia.

## Zobacz także

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