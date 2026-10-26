---
title: idx_get()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει ένα cookie από τη συλλογή cookie στον καθορισμένο δείκτη.
type: docs
weight: 40
url: /el/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) μέθοδος

Επιστρέφει ένα cookie από τη συλλογή cookie στο συγκεκριμένο δείκτη.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης του cookie που πρέπει να επιστραφεί. |

### Τιμή Επιστροφής

Ένα cookie στο συγκεκριμένο δείκτη.

## CookieCollection::idx_get(String) μέθοδος

Επιστρέφει ένα cookie από τη συλλογή cookie με το συγκεκριμένο όνομα.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Το όνομα του cookie που πρέπει να επιστραφεί. |

### Τιμή Επιστροφής

Ένα cookie από τη συλλογή cookie με το συγκεκριμένο όνομα όταν βρεθεί, διαφορετικά nullptr.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Cookie](../../cookie/)
* Κλάση [CookieCollection](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)