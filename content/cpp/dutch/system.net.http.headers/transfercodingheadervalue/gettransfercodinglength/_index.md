---
title: GetTransferCodingLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een meegegeven string vanaf de gespecificeerde index naar een instantie van de TransferCodingHeaderValue klasse.
type: docs
weight: 105
url: /nl/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) methode

Converteert een meegegeven string vanaf de gespecificeerde index naar een instantie van de [TransferCodingHeaderValue](../) klasse.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [String](../../../system/string/) | Een string om te parseren. |
| startIndex | **int32_t** | Een startpositie voor het parseren. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Een instantie waarin een geparseerd object wordt toegewezen. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | De delegate die wordt gebruikt om instanties van de [TransferCodingHeaderValue](../) klasse te creëren. |

### Retourwaarde

Retourneert de lengte van een geparseerde subreeks, anders 0.

## Zie ook

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [TransferCodingHeaderValue](../)
* Naamruimte [System::Net::Http::Headers](../../)
* Bibliotheek [Aspose.Slides](../../../)