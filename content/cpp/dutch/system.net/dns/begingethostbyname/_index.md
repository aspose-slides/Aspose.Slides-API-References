---
title: BeginGetHostByName()
second_title: Aspose.Slides voor C++ API-referentie
description: Start een asynchrone bewerking om een nieuw IPHostEntry-class instance te maken met de opgegeven hostnaam.
type: docs
weight: 53
url: /nl/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) methode

Start een asynchrone bewerking om een nieuw IPHostEntry-class instance te maken met de opgegeven hostnaam.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Een hostnaam. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking voltooid is. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Gebruiker-geleverde gegevens die worden gebruikt om elke asynchrone bewerking uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone bewerking vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Klasse [Dns](../)
* Namespace [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)