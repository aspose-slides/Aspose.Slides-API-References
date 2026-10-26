---
title: BeginRead()
second_title: Aspose.Slides voor C++ API-referentie
description: Initieert een asynchrone leesoperatie.
type: docs
weight: 417
url: /nl/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) methode

Initieert een asynchrone leesoperatie.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array om gegevens uit te lezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| count | **int32_t** | Het aantal bytes om te lezen. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Gebruiker-geleverde data die wordt gebruikt om elke asynchrone leesoperatie uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/)-object dat de geïnitieerde asynchrone leesoperatie voorstelt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [SslStream](../)
* Naamruimte [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)