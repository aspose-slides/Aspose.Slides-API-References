---
title: GetRangeItemListLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een doorgegeven string vanaf de opgegeven positie naar de collectie van RangeItemHeaderValue-class-instanties.
type: docs
weight: 79
url: /nl/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) methode


Converteert een doorgegeven string vanaf de opgegeven positie naar de collectie van RangeItemHeaderValue-class-instanties.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [String](../../../system/string/) | Een string om te parseren. |
| startIndex | **int32_t** | Een startpositie voor het parseren. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Een instantie waarin een geparseerde collectie zal worden toegewezen. |

### Retourwaarde

De lengte van een geparseerde substring, anders 0.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ICollection](../../../system.collections.generic/icollection/)
* Klasse [RangeItemHeaderValue](../)
* Naamruimte [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)