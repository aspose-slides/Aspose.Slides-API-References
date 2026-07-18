---
title: MakeYieldEnumerable()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα IEnumerable από μια συνάρτηση απόδοσης.
type: docs
weight: 2380
url: /el/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) συνάρτηση


Δημιουργεί ένα IEnumerable από μια συνάρτηση απόδοσης.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στη σειρά |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Η συνάρτηση απόδοσης που θα εκτελεστεί |

### Τιμή επιστροφής

Κοινός δείκτης προς το IEnumerable

## Δείτε επίσης

* Τύπος [SharedPtr](../sharedptr/)
* Κλάση [IEnumerable](../../system.collections.generic/ienumerable/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)