---
title: GetCustomAttributes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν όλα τα προσαρμοσμένα χαρακτηριστικά που εφαρμόζονται στον τύπο.
type: docs
weight: 586
url: /el/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const method


Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν όλα τα προσαρμοσμένα χαρακτηριστικά που εφαρμόζονται στον τύπο.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const method


Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν συγκεκριμένα χαρακτηριστικά που εφαρμόζονται στον τύπο.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Τύπος του χαρακτηριστικού που αναζητείται. |
| inherit | **bool** | Καθορίζει εάν θα αναζητηθούν επίσης κληρονομικά χαρακτηριστικά. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [SmartPtr](../../smartptr/)
* Κλάση [TypeInfo](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)