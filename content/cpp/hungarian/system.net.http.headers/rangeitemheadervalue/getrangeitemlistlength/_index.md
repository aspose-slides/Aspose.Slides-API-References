---
title: GetRangeItemListLength()
second_title: Aspose.Slides a C++ API hivatkozás
description: Átalakítja a megadott karakterláncot a meghatározott pozíciótól a RangeItemHeaderValue-class példányok gyűjteményébe.
type: docs
weight: 79
url: /hu/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) method


Átalakítja a megadott karakterláncot a megadott pozíciótól a RangeItemHeaderValue osztály példányainak gyűjteményébe.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| startIndex | **int32_t** | A feldolgozás kezdőpozíciója. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Egy példány, amelybe a feldolgozott gyűjtemény lesz hozzárendelve. |

### Visszatérési érték

A feldolgozott részkarakterlánc hossza, egyébként 0.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)