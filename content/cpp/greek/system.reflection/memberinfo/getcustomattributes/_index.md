---
title: GetCustomAttributes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν όλα τα προσαρμοσμένα χαρακτηριστικά που έχουν εφαρμοστεί στον τύπο που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 66
url: /el/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const μέθοδος

Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν όλα τα προσαρμοσμένα χαρακτηριστικά που έχουν εφαρμοστεί στον τύπο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Τύπος χαρακτηριστικού που πρέπει να αναζητηθεί. |
| inherit | **bool** | Κατά πόσο θα ελεγχθούν επίσης τα κληρονομημένα χαρακτηριστικά. |

## MemberInfo::GetCustomAttributes(bool) const μέθοδος

Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν όλα τα προσαρμοσμένα χαρακτηριστικά που έχουν εφαρμοστεί στον τύπο που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| inherit | **bool** | Κατά πόσο θα ελεγχθούν επίσης τα κληρονομημένα χαρακτηριστικά. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [MemberInfo](../)
* Χώρος ονομάτων [System::Reflection](../../)
* Library [Aspose.Slides](../../../)