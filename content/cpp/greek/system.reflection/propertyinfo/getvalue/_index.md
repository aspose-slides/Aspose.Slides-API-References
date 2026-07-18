---
title: GetValue()
second_title: Aspose.Slides για την αναφορά API του C++
description: Αποκτά την τιμή της ιδιότητας από ένα συγκεκριμένο αντικείμενο.
type: docs
weight: 1
url: /el/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) μέθοδος

Αποκτά την τιμή της ιδιότητας από ένα συγκεκριμένο αντικείμενο.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) για την ανάγνωση της ιδιότητας από. |

### Τιμή Επιστροφής

Τιμή της καθορισμένης ιδιότητας για το συγκεκριμένο αντικείμενο.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) μέθοδος

Αποκτά την τιμή της ιδιότητας από ένα συγκεκριμένο αντικείμενο.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) για την ανάγνωση της ιδιότητας από. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Αυτές είναι προαιρετικές τιμές ευρετηρίου για ιδιότητες με δείκτη. Για ιδιότητες χωρίς δείκτη, αυτή η τιμή πρέπει να είναι null. |

### Τιμή Επιστροφής

Τιμή της καθορισμένης ιδιότητας για το συγκεκριμένο αντικείμενο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [PropertyInfo](../)
* Χώρος ονομάτων [System::Reflection](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)