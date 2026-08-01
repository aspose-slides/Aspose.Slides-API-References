---
title: CollectionAssertHelper
second_title: Aspose.Slides voor C++ API-referentie
description: Heler API voor collectiegerelateerde bewerkingen.
type: docs
weight: 1548
url: /nl/system/collectionasserthelper/
---
## CollectionAssertHelper struct

Heler API voor collection-gerelateerde bewerkingen.

```cpp
class CollectionAssertHelper
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Controleert of alle elementen van de collectie voldoen aan het predikaat. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Controleert of een willekeurig element van de collectie voldoet aan het predikaat. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serialiseert twee collecties voor berichtrepresentatie. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Converteert een collectie naar een string door de tekenreeksrepresentaties van elementen samen te voegen. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Berekent 'diff' tussen twee collecties. Voor elk element van elke collectie als sleutel zal de resulterende waarde positief zijn als het element vaker voorkomt in de \"expected\" collectie, negatief als het element vaker voorkomt in de \"actual\" collectie, en nul als het element even vaak voorkomt in beide collecties. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formateert een string die gebruikt wordt als berichttekst. |
## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)