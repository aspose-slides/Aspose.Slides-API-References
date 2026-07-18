---
title: UnboxToNullable()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποσυσκευάζει το αντικείμενο σε nullable τύπο.
type: docs
weight: 79
url: /el/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) μέθοδος

Αποσυσκευάζει το αντικείμενο σε nullable τύπο.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος προορισμού. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) για αποσυσκευασία. |
| safe | **bool** | Εάν είναι true, επιστρέφει nullptr κατά την αποτυχία, αλλιώς ρίχνει InvalidCastException. |

### Τιμή Επιστροφής

Τιμή nullable που αποσυσκευάστηκε (μπορεί να είναι null).

## Δείτε επίσης

* Κλάση [Nullable](../../nullable/)
* Κλάση [SmartPtr](../../smartptr/)
* Κλάση [Object](../../object/)
* Κλάση [ObjectExt](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)