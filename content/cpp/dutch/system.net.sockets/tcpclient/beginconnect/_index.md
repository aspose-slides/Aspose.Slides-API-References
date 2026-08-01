---
title: BeginConnect()
second_title: Aspose.Slides voor C++ API-referentie
description: Initieert een asynchrone verbindingsoperatie.
type: docs
weight: 261
url: /nl/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) methode


Initieert een asynchrone verbindingsoperatie.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | [String](../../../system/string/) | Een externe hostnaam. |
| port | **int32_t** | Een poort van de externe host. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone verbindingsoperatie uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone verbindingsoperatie vertegenwoordigt.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) methode


Initieert een asynchrone verbindingsoperatie.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Het IP-adres van een externe host. |
| port | **int32_t** | Een poort van de externe host. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone verbindingsoperatie uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone verbindingsoperatie vertegenwoordigt.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) methode


Initieert een asynchrone verbindingsoperatie.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | De IP-adressen van een externe host. |
| port | **int32_t** | Een poort van de externe host. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone verbindingsoperatie uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone verbindingsoperatie vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Klasse [TcpClient](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)