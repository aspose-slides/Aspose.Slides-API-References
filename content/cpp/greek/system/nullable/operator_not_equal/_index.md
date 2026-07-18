---
title: operator!=()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο δεν είναι null.
type: docs
weight: 144
url: /el/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const μέθοδος

Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο δεν είναι null.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```

### Τιμή Επιστροφής

Αληθές αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο δεν είναι null, διαφορετικά - ψευδές

## Nullable::operator!=(const T1\&) const μέθοδος

Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο δεν είναι ίση με την καθορισμένη τιμή.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```

### Παράμετροι Προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Ο τύπος της τιμής για σύγκριση |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Μια σταθερή αναφορά στην τιμή για σύγκριση |

### Τιμή Επιστροφής

Αληθές αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο δεν είναι ίση με την καθορισμένη τιμή, διαφορετικά - ψευδές

## Nullable::operator!=(const Nullable\<T1\>\&) const μέθοδος

Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο δεν είναι ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο [Nullable](../) αντικείμενο.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```

### Παράμετροι Προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Ο βασικός τύπος του [Nullable](../) αντικειμένου για σύγκριση |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Μια σταθερή αναφορά στο [Nullable](../) αντικείμενο για σύγκριση |

### Τιμή Επιστροφής

Αληθές αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο δεν είναι ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο [Nullable](../) αντικείμενο, διαφορετικά - ψευδές

## Δείτε Επίσης

* Κλάση [Nullable](../)
* Δομή [IsNullable](../../isnullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)