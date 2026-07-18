---
title: MakeObject()
second_title: Aspose.Slides για το C++ API Αναφορά
description: Δημιουργεί αντικείμενο στο heap και επιστρέφει κοινό δείκτη σε αυτό.
type: docs
weight: 2848
url: /el/system/makeobject/
---
## System::MakeObject(Args\&&...) συνάρτηση

Δημιουργεί αντικείμενο στο heap και επιστρέφει κοινό δείκτη σε αυτό.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Κλάση για δημιουργία. |
| Args | Τύποι ορισμάτων κατασκευής. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | Args\&&... | Ορίσματα κατασκευής. |

### Τιμή επιστροφής

[SmartPtr](../smartptr/) σε νεοδημιουργημένο αντικείμενο, πάντα σε κοινή λειτουργία.

## System::MakeObject(Args\&&...) συνάρτηση

Δημιουργεί αντικείμενο στο heap και επιστρέφει κοινό δείκτη σε αυτό.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [SmartPtr](../smartptr/) στην κλάση για δημιουργία. |
| Args | Τύποι ορισμάτων κατασκευής. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | Args\&&... | Ορίσματα κατασκευής. |

### Τιμή επιστροφής

[SmartPtr](../smartptr/) σε νεοδημιουργημένο αντικείμενο, πάντα σε κοινή λειτουργία.

## Δες επίσης

* Κλάση [SmartPtr](../smartptr/)
* Δομή [IsSmartPtr](../issmartptr/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)