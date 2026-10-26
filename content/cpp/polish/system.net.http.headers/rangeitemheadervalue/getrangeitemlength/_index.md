---
title: GetRangeItemLength()
second_title: Referencja API Aspose.Slides dla C++
description: Konwertuje podany ciąg znaków od określonego indeksu na instancję klasy RangeItemHeaderValue.
type: docs
weight: 92
url: /pl/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) metoda

Konwertuje podany ciąg znaków od określonego indeksu do instancji klasy [RangeItemHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do parsowania. |
| startIndex | **int32_t** | Pozycja początkowa do parsowania. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | Instancja, w której zostanie przypisany przetworzony obiekt. |

## Wartość zwracana

Zwraca długość przetworzonego podciągu, w przeciwnym razie 0.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [RangeItemHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)