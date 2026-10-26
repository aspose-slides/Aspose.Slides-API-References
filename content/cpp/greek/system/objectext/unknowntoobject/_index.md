---
title: UnknownToObject()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει άγνωστο τύπο σε Object, χειρίζοντας τόσο τύπους έξυπνων δεικτών όσο και τύπους τιμών.
type: docs
weight: 118
url: /el/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) μέθοδος


Μετατρέπει άγνωστο τύπο σε [Object](../../object/), χειρίζοντας τόσο τύπους έξυπνων δεικτών όσο και τύπους τιμών.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος για μετατροπή σε [Object](../../object/). |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T | [Object](../../object/) για μετατροπή. |

### Τιμή επιστροφής

Έξυπνος δείκτης προς [Object](../../object/), ο οποίος είναι είτε μετατρεπόμενος δείκτης είτε τιμή σε κέλυφος.

## ObjectExt::UnknownToObject(const T\&) μέθοδος


Μετατρέπει άγνωστο τύπο σε [Object](../../object/), χειρίζοντας τόσο τύπους έξυπνων δεικτών όσο και τύπους τιμών.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος για μετατροπή σε [Object](../../object/). |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) για μετατροπή. |

### Τιμή επιστροφής

Έξυπνος δείκτης προς [Object](../../object/), ο οποίος είναι είτε μετατρεπόμενος δείκτης είτε τιμή σε κέλυφος.

## Δείτε επίσης

* Κλάση [SmartPtr](../../smartptr/)
* Κλάση [Object](../../object/)
* Κλάση [ObjectExt](../)
* Δομή [IsSmartPtr](../../issmartptr/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)