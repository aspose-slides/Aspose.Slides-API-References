---
title: GetTransferCodingLength()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy TransferCodingHeaderValue.
type: docs
weight: 105
url: /pl/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) metoda

Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do parsowania. |
| startIndex | **int32_t** | Pozycja początkowa do parsowania. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Instancja, do której zostanie przypisany sparsowany obiekt. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Delegat używany do tworzenia instancji klasy [TransferCodingHeaderValue](../). |

### Wartość zwracana

Zwraca długość sparsowanego podciągu, w przeciwnym razie 0.

## Zobacz także

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [TransferCodingHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)