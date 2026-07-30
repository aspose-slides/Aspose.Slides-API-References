---
title: GetRangeItemLength()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí předaný řetězec od zadaného indexu na instanci třídy RangeItemHeaderValue.
type: docs
weight: 92
url: /cs/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) metoda

Převádí předaný řetězec od zadaného indexu na instanci třídy [RangeItemHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Řetězec k analýze. |
| startIndex | **int32_t** | Počáteční pozice pro analýzu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | Instance, do které bude přiřazen analyzovaný objekt. |

### Návratová hodnota

Vrací délku analyzovaného podřetězce, jinak 0.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [RangeItemHeaderValue](../)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)