---
title: CheckDiffForAny()
second_title: Aspose.Slides C++ API-referencia
description: Ellenőrzi, hogy a gyűjtemény bármely eleme megfelel-e a predikátumnak.
type: docs
weight: 27
url: /hu/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method


Ellenőrzi, hogy a gyűjtemény bármely eleme megfelel-e a predikátumnak.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicate to check. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Values to check. |

### Visszatérési érték

True if check suceeds for any element, false if all pass.

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [ICollection](../../../system.collections.generic/icollection/)
* Struktúra [CollectionAssertHelper](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)