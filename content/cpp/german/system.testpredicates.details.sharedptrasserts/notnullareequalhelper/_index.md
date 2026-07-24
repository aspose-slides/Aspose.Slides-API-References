---
title: NotNullAreEqualHelper()
second_title: Aspose.Slides für C++ API Referenz
description: Vergleicht abstrakte Sammlungen auf Gleichheit.
type: docs
weight: 66
url: /de/system.testpredicates.details.sharedptrasserts/notnullareequalhelper/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

Vergleicht abstrakte Sammlungen auf Gleichheit.

```cpp
template<typename T> bool System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Elementtyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Linker Wert. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Rechter Wert. |

### Rückgabewert

gtest-stil Assertionsergebnis.

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [ICollection](../../system.collections.generic/icollection/)
* Namensraum [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliothek [Aspose.Slides](../../)