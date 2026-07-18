---
title: ToArray()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια.
type: docs
weight: 105
url: /el/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() μέθοδος


Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### Τιμή επιστροφής

Πίνακας των [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) μέθοδος


Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια από το καθορισμένο εύρος.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | **int32_t** | Ένας δείκτης του πρώτου σχολίου που θα επιστραφεί. |
| count | **int32_t** | Αριθμός σχολίων που θα επιστραφούν. |

### Τιμή επιστροφής

Πίνακας των [Comment](../../comment/).

## Δείτε επίσης

* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IComment](../../icomment/)
* Κλάση [CommentCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)