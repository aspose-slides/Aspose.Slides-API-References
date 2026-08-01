---
title: EndGetHostAddresses()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot de opgegeven asynchrone bewerking om een nieuw IPHostEntry-class-instance te maken voltooid is.
type: docs
weight: 144
url: /nl/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) methode

Wacht tot de opgegeven asynchrone bewerking om een nieuw IPHostEntry-class-instance te maken voltooid is.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone bewerking vertegenwoordigt. |

### Retourwaarde

Een nieuw aangemaakt IPHostEntry-class-instance.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPAddress](../../ipaddress/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Dns](../)
* Naamruimte [System::Net](../../)
* Library [Aspose.Slides](../../../)