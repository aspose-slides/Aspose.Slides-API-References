---
title: BeginGetHostAddresses()
second_title: Aspose.Slides voor C++ API-referentie
description: Start een asynchrone bewerking om een nieuw IPHostEntry-class instance te creëren met de opgegeven string die een hostnaam of IP-adres bevat.
type: docs
weight: 131
url: /nl/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) methode

Start een asynchrone bewerking om een nieuw IPHostEntry-class instance te maken met de opgegeven string die een hostnaam of IP-adres bevat.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Een string die een hostnaam of IP-adres bevat. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking voltooid is. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Gebruiker geleverde gegevens die worden gebruikt om elke asynchrone bewerking uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/)-object dat de gestartte asynchrone bewerking weergeeft.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Klasse [Dns](../)
* Naamruimte [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)