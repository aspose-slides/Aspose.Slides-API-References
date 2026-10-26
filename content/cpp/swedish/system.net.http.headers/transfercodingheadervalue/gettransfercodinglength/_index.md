---
title: GetTransferCodingLength()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en given sträng från det angivna indexet till en instans av klassen TransferCodingHeaderValue.
type: docs
weight: 105
url: /sv/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) metod

Konverterar en given sträng från det angivna indexet till en instans av [TransferCodingHeaderValue](../) klass.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att tolka. |
| startIndex | **int32_t** | En startposition för tolkning. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | En instans där ett tolkat objekt kommer att tilldelas. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Delegaten som används för att skapa instanser av [TransferCodingHeaderValue](../)-klassen. |

### Returvärde

Returnerar längden på en tolkad delsträng, annars 0.

## Se även

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)