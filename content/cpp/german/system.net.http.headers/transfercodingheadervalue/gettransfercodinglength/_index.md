---
title: GetTransferCodingLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert eine übergebene Zeichenkette ab dem angegebenen Index in eine Instanz der TransferCodingHeaderValue Klasse.
type: docs
weight: 105
url: /de/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) Methode


Konvertiert eine übergebene Zeichenkette ab dem angegebenen Index in eine Instanz der [TransferCodingHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Eine zu parsende Zeichenkette. |
| startIndex | **int32_t** | Eine Startposition zum Parsen. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Eine Instanz, in der ein geparstes Objekt zugewiesen wird. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Der Delegat, der verwendet wird, um Instanzen der [TransferCodingHeaderValue](../) Klasse zu erstellen. |

### Rückgabewert

Gibt die Länge einer geparsten Teilzeichenkette zurück, andernfalls 0.

## Siehe auch

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [TransferCodingHeaderValue](../)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)