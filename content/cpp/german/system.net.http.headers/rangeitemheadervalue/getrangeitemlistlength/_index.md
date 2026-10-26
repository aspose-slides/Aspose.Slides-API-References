---
title: GetRangeItemListLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert einen übergebenen String ab der angegebenen Position in die Sammlung von RangeItemHeaderValue-Klasseninstanzen.
type: docs
weight: 79
url: /de/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) Methode


Konvertiert einen übergebenen String ab der angegebenen Position in die Sammlung von RangeItemHeaderValue-Klasseninstanzen.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ein String zum Parsen. |
| startIndex | **int32_t** | Eine Startposition zum Parsen. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Eine Instanz, in die eine geparste Sammlung zugewiesen wird. |

### Rückgabewert

Die Länge einer geparsten Teilzeichenkette, andernfalls 0.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)