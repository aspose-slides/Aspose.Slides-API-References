---
title: ObjectToUnknown()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει Object σε άγνωστο τύπο, χειρίζεται τόσο τον τύπο smart pointer όσο και καταστάσεις με bpxed τιμές.
type: docs
weight: 131
url: /el/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) μέθοδος

Μετατρέπει [Object](../../object/) σε άγνωστο τύπο, χειρίζεται τόσο τον τύπο smart pointer όσο και καταστάσεις με τιμή bpxed.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος στον οποίο θα μετατραπεί [Object](../../object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) για μετατροπή. |

### Τιμή επιστροφής

Είτε μη συσκευασμένη τιμή είτε μετατρεπόμενος δείκτης.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) μέθοδος

Μετατρέπει [Object](../../object/) σε άγνωστο τύπο, χειρίζεται τόσο τον τύπο smart pointer όσο και καταστάσεις με τιμή boxed.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος στον οποίο θα μετατραπεί [Object](../../object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) για μετατροπή. |

### Τιμή επιστροφής

Είτε μη συσκευασμένη τιμή είτε μετατρεπόμενος δείκτης.

## Δείτε επίσης

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)