---
title: ForceStaticCast()
second_title: Αναφορά API Aspose.Slides για C++
description: Εκτελεί πραγματική στατική μετατροπή σε αντικείμενα SmartPtr.
type: docs
weight: 2549
url: /el/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) συνάρτηση

Εκτελεί πραγματική στατική μετατροπή σε αντικείμενα [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος του δείκτη-στόχου. |
| TFrom | Τύπος του δείκτη-προέλευσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Δείκτης προέλευσης. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή είναι επιτρεπτή, διαφορετικά η συμπεριφορά είναι αόριστη.

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Δομή [CastResult](../castresult/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)