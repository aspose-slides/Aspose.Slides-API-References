---
title: BeginConnect()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Rozpoczyna asynchroniczną operację połączenia.
type: docs
weight: 573
url: /pl/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) metoda

Rozpoczyna asynchroniczną operację połączenia.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Funkcja zwrotna, która zostanie wywołana po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji połączenia. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący rozpoczętą asynchroniczną operację połączenia.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Rozpoczyna asynchroniczną operację połączenia.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nazwa zdalnego hosta. |
| port | **int32_t** | Numer portu zdalnego hosta. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Funkcja zwrotna, która zostanie wywołana po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji połączenia. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący rozpoczętą asynchroniczną operację połączenia.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Rozpoczyna asynchroniczną operację połączenia.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Adres IP zdalnego hosta. |
| port | **int32_t** | Numer portu zdalnego hosta. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Funkcja zwrotna, która zostanie wywołana po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji połączenia. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący rozpoczętą asynchroniczną operację połączenia.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Rozpoczyna asynchroniczną operację połączenia.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Adresy IP zdalnego hosta. |
| port | **int32_t** | Numer portu zdalnego hosta. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Funkcja zwrotna, która zostanie wywołana po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji połączenia. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący rozpoczętą asynchroniczną operację połączenia.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [EndPoint](../../../system.net/endpoint/)
* Klasa [Object](../../../system/object/)
* Klasa [Socket](../)
* Klasa [String](../../../system/string/)
* Klasa [IPAddress](../../../system.net/ipaddress/)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)