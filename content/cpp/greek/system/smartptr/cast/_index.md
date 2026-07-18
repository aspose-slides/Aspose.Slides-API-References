---
title: Cast()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει τον δείκτη στον ίδιο του τύπο.
type: docs
weight: 287
url: /el/system/smartptr/cast/
---
## SmartPtr::Cast() const μέθοδος

Μετατρέπει τον δείκτη σε τύπο του ίδιου.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Y | Τύπος-στόχος του αντικειμένου που επισημαίνεται. |
| Check | Σημαίες για ρίψη εξαίρεσης εάν δεν υπάρχει διαθέσιμη μετατροπή. |

### Τιμή επιστροφής

Δείκτης αλλαγμένου τύπου, ο οποίος είναι πάντα σε κοινή λειτουργία.

## SmartPtr::Cast() const μέθοδος

Μετατρέπει τον δείκτη σε τύπο βάσης χρησιμοποιώντας static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Y | Τύπος-στόχος του αντικειμένου που επισημαίνεται. |
| Check | Σημαίες για ρίψη εξαίρεσης εάν δεν υπάρχει διαθέσιμη μετατροπή. |

### Τιμή επιστροφής

Δείκτης αλλαγμένου τύπου, ο οποίος είναι πάντα σε κοινή λειτουργία.

## SmartPtr::Cast() const μέθοδος

Μετατρέπει τον δείκτη σε παραγόμενο τύπο με dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Y | Τύπος-στόχος του αντικειμένου που επισημαίνεται. |
| Check | Σημαίες για ρίψη εξαίρεσης εάν δεν υπάρχει διαθέσιμη μετατροπή. |

### Τιμή επιστροφής

Δείκτης αλλαγμένου τύπου, ο οποίος είναι πάντα σε κοινή λειτουργία. Ρίχνει InvalidCastException εάν δεν υπάρχει διαθέσιμη μετατροπή.

## SmartPtr::Cast() const μέθοδος

Μετατρέπει τον δείκτη σε παραγόμενο τύπο με dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Y | Τύπος-στόχος του αντικειμένου που επισημαίνεται. |
| Check | Σημαίες για ρίψη εξαίρεσης εάν δεν υπάρχει διαθέσιμη μετατροπή. |

### Τιμή επιστροφής

Δείκτης αλλαγμένου τύπου, ο οποίος είναι πάντα σε κοινή λειτουργία. Επιστρέφει nullptr εάν δεν υπάρχει διαθέσιμη μετατροπή.

## Δείτε επίσης

* Κλάση [SmartPtr](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)