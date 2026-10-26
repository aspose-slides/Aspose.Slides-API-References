---
title: EndRead()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot de opgegeven asynchrone leesbewerking voltooid is.
type: docs
weight: 261
url: /nl/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) methode

Wacht tot de opgegeven asynchrone leesbewerking voltooid is.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone leesbewerking vertegenwoordigt |

### Retourwaarde

Het aantal bytes dat gelezen is tijdens de leesbewerking die wordt vertegenwoordigd door **asyncResult**

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [NetworkStream](../)
* Naamruimte [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)