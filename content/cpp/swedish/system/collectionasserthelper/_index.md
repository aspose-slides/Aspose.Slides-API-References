---
title: CollectionAssertHelper
second_title: Aspose.Slides för C++ API-referens
description: Hjälp-API för samlingsrelaterade operationer.
type: docs
weight: 1548
url: /sv/system/collectionasserthelper/
---
## CollectionAssertHelper struct

Helper API för samlingsrelaterade operationer.

```cpp
class CollectionAssertHelper
```

## Methods

| Metod | Beskrivning |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Kontrollerar att alla samlingselement följer predikatet. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Kontrollerar att något samlingselement följer predikatet. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serialiserar två samlingar för meddelanderepresentation. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Omvandlar samling till sträng genom att sammanfoga elementens strängrepresentationer. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Beräknar 'diff' mellan två samlingar. För varje element i varje samling som nyckel blir det resulterande värdet positivt om elementet förekommer fler gånger i den \"expected\" samlingen, negativt om elementet förekommer fler gånger i den \"actual\" samlingen, och noll om elementet förekommer lika många gånger i båda samlingarna. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formaterar sträng för att användas som meddelandetext. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)