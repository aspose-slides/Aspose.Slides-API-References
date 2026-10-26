---
title: EndRead()
second_title: Aspose.Slides for C++ API Referentie
description: Wacht tot de opgegeven asynchrone leesbewerking is voltooid.
type: docs
weight: 430
url: /nl/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) methode

Wacht tot de opgegeven asynchrone leesbewerking is voltooid.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone leesbewerking vertegenwoordigt |

### Retourwaarde

Het aantal bytes dat is gelezen tijdens de leesbewerking die wordt weergegeven door **asyncResult**

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [SslStream](../)
* Naamruimte [System::Net::Security](../../)
* Bibliotheek [Aspose.Slides](../../../)