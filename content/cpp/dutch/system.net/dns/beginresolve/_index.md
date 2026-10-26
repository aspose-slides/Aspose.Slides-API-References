---
title: BeginResolve()
second_title: Aspose.Slides voor C++ API-referentie
description: Start een asynchrone bewerking om een nieuw IPHostEntry-klasse-instance te maken met de opgegeven hostnaam.
type: docs
weight: 157
url: /nl/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) methode

Initialiseert een asynchrone bewerking om een nieuw IPHostEntry-klasse-instance te maken met de opgegeven hostnaam.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Een hostnaam die wordt gebruikt om een nieuw exemplaar van de [IPHostEntry](../../iphostentry/) klasse te maken. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker aangeleverde gegevens die worden gebruikt om elke asynchrone bewerking uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/)-object dat de geïnitieerde asynchrone bewerking vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)