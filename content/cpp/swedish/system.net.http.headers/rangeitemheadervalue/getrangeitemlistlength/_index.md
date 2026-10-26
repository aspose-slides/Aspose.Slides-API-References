---
title: GetRangeItemListLength()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en given sträng från den specificerade positionen till samlingen av RangeItemHeaderValue-klassinstanser.
type: docs
weight: 79
url: /sv/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) metod


Konverterar en given sträng från den specificerade positionen till samlingen av RangeItemHeaderValue-klassinstanser.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att analysera. |
| startIndex | **int32_t** | En startposition för analysering. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | En instans där en analyserad samling kommer att tilldelas. |

## Returvärde

Längden på en analyserad delsträng, annars 0.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [ICollection](../../../system.collections.generic/icollection/)
* Klass [RangeItemHeaderValue](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)