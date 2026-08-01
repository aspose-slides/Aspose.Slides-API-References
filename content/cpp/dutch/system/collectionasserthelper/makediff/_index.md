---
title: MakeDiff()
second_title: Aspose.Slides voor C++ API-referentie
description: Bereken 'diff' tussen twee collecties. Voor elk element van elke collectie als sleutel zal de resulterende waarde positief zijn als het element vaker voorkomt in \"expected\" collectie, negatief als het element vaker voorkomt in \"actual\" collectie, en nul als het element even vaak voorkomt in elke collectie.
type: docs
weight: 1
url: /nl/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) methode

Bereken 'diff' tussen twee collecties. Voor elk element van elke collectie als sleutel zal de resulterende waarde positief zijn als het element vaker voorkomt in de \"expected\" collectie, negatief als het element vaker voorkomt in de \"actual\" collectie, en nul als het element even vaak voorkomt in elke collectie.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Expected collection element type. |
| T2 | Actual collection element type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Expected collection. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Actual collecion. |

### Retourwaarde

Map of per-value comparison results as per rules above.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)