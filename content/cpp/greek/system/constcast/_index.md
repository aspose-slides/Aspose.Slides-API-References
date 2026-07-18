---
title: ConstCast()
second_title: Aspose.Slides για την αναφορά API του C++
description: Τέλος των αποσυρμένων μετατροπών.
type: docs
weight: 2536
url: /el/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) συνάρτηση


Τέλος των αποσυρμένων μετατροπών.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος δείκτη προορισμού. |
| TFrom | Τύπος δείκτη πηγής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Δείκτης πηγής. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται ή nullptr διαφορετικά.
## Παρατηρήσεις


Εκτελεί const cast σε αντικείμενα [SmartPtr](../smartptr/).
## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Δομή [CastResult](../castresult/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)