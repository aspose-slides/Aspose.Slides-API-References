---
title: Cast_noexcept()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εκτελεί μετατροπή σε αντικείμενα SmartPtr.
type: docs
weight: 2458
url: /el/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) συνάρτηση

Εκτελεί μετατροπή σε αντικείμενα [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος δείκτη-στόχου. |
| TFrom | Τύπος δείκτη-προέλευσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Δείκτης προέλευσης. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή είναι επιτρεπτή ή nullptr σε αντίθετη περίπτωση.

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Δομή [IsExceptionWrapper](../isexceptionwrapper/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)