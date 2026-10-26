---
title: GetRangeItemListLength()
second_title: Aspose.Slides pro C++ API referenci
description: Převede předaný řetězec ze specifikované pozice do kolekce instancí třídy RangeItemHeaderValue.
type: docs
weight: 79
url: /cs/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) metoda


Převede předaný řetězec ze specifikované pozice do kolekce instancí třídy RangeItemHeaderValue.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Řetězec k analýze. |
| startIndex | **int32_t** | Počáteční pozice pro parsování. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Instance, do které bude přiřazena analyzovaná kolekce. |

### Návratová hodnota

Délka analyzovaného podřetězce, jinak 0.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [ICollection](../../../system.collections.generic/icollection/)
* Třída [RangeItemHeaderValue](../)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)