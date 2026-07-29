---
title: MakeDiff()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar 'diff' mellan två samlingar. För varje element i varje samling som nyckel blir det resulterande värdet positivt om elementet förekommer fler gånger i \"expected\" samlingen, negativt om elementet förekommer fler gånger i \"actual\" samlingen, och noll om elementet förekommer lika många gånger i varje samling.
type: docs
weight: 1
url: /sv/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metod


Beräknar 'diff' mellan två samlingar. För varje element i varje samling som nyckel blir det resulterande värdet positivt om elementet förekommer fler gånger i "expected" samlingen, negativt om elementet förekommer fler gånger i "actual" samlingen, och noll om elementet förekommer lika många gånger i varje samling.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av element i förväntad samling. |
| T2 | Typ av element i faktisk samling. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Förväntad samling. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Faktisk samling. |

### Returvärde

Karta med per-värde jämförelseresultat enligt reglerna ovan.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Dictionary](../../../system.collections.generic/dictionary/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktur [CollectionAssertHelper](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)