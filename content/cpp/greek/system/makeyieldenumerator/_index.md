---
title: MakeYieldEnumerator()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα IEnumerator από μια συνάρτηση παραγωγής.
type: docs
weight: 2393
url: /el/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) συνάρτηση

Δημιουργεί ένα IEnumerator από μια συνάρτηση παραγωγής.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στη σειρά |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Η συνάρτηση παραγωγής προς εκτέλεση |

### Τιμή Επιστροφής

Κοινός δείκτης προς το IEnumerator

## Δείτε επίσης

* Δήλωση τύπου [SharedPtr](../sharedptr/)
* Κλάση [IEnumerator](../../system.collections.generic/ienumerator/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)