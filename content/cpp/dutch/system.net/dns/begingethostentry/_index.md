---
title: BeginGetHostEntry()
second_title: Aspose.Slides voor C++ API-referentie
description: Start een asynchrone bewerking om een nieuwe IPHostEntry-class instantie te maken met de opgegeven tekenreeks die een hostnaam of IP-adres bevat.
type: docs
weight: 105
url: /nl/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) methode


Start een asynchrone bewerking om een nieuwe IPHostEntry-class-instantie te maken met de opgegeven tekenreeks die een hostnaam of IP-adres bevat.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | De tekenreeks die een hostnaam of IP-adres bevat. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen zodra de bewerking is voltooid. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die elke asynchrone bewerking uniek identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de gestart-asynchrone bewerking vertegenwoordigt.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) methode


Start een asynchrone bewerking om een nieuwe IPHostEntry-class-instantie te maken met het opgegeven IP-adres.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Het IP-adres. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen zodra de bewerking is voltooid. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die elke asynchrone bewerking uniek identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de gestart-asynchrone bewerking vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Klasse [Dns](../)
* Klasse [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)