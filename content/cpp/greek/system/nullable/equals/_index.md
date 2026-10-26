---
title: Equals()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο Nullable αντικείμενο.
type: docs
weight: 131
url: /el/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const μέθοδος


Καθορίζει αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο [Nullable](../) αντικείμενο.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Ο υποκείμενος τύπος του αντικειμένου [Nullable](../) για σύγκριση |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Μια σταθερή αναφορά στο αντικείμενο [Nullable](../) για σύγκριση |

### Τιμή επιστροφής

Αληθές εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο [Nullable](../) αντικείμενο, διαφορετικά - ψευδές

## Δείτε επίσης

* Κλάση [Nullable](../)
* Δομή [IsNullable](../../isnullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)