---
title: Cast()
second_title: Αναφορά API Aspose.Slides για C++
description: Εκτελεί μετατροπή σε αντικείμενα SmartPtr.
type: docs
weight: 2471
url: /el/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) συνάρτηση

Εκτελεί μετατροπή σε αντικείμενα [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TTo | Τύπος δείκτη προορισμού. |
| TFrom | Τύπος δείκτη προέλευσης. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Δείκτης προέλευσης. |

### Τιμή επιστροφής

Αποτέλεσμα της μετατροπής εάν η μετατροπή επιτρέπεται.

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Δομή [IsExceptionWrapper](../isexceptionwrapper/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)