---
title: MakeDiff()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet die 'diff' zwischen zwei Sammlungen. Für jedes Element jeder Sammlung als Schlüssel wird das Ergebnis positiv sein, wenn das Element öfter in der \"expected\"-Sammlung vorkommt, negativ, wenn das Element öfter in der \"actual\"-Sammlung vorkommt, und null, wenn das Element in beiden Sammlungen gleich oft vorkommt.
type: docs
weight: 1
url: /de/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method

Berechnet die \"diff\" zwischen zwei Sammlungen. Für jedes Element jeder Sammlung wird das resultierende Ergebnis als Schlüssel positiv sein, wenn das Element häufiger in der \"expected\"-Sammlung vorkommt, negativ, wenn das Element häufiger in der \"actual\"-Sammlung vorkommt, und null, wenn das Element in beiden Sammlungen gleich oft vorkommt.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Expected collection element type. |
| T2 | Actual collection element type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Expected collection. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Actual collecion. |

### Rückgabewert

Map of per-value comparison results as per rules above.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Dictionary](../../../system.collections.generic/dictionary/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)