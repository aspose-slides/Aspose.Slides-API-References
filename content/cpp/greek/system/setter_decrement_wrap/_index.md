---
title: setter_decrement_wrap()
second_title: Aspose.Slides για το API Αναφορά C++
description: Ο μεταφραστής μεταφράζει τις προ-απενεργοποιήσεις του C# που στοχεύουν σε ιδιότητα κλάσης που έχει ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης.
type: docs
weight: 2822
url: /el/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) συνάρτηση

Ο μεταφραστής μεταφράζει τις προ-απενεργοποιήσεις του C# που στοχεύουν σε ιδιότητα κλάσης που έχει ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pGetter | T(*)() | Δείκτης συνάρτησης που δείχνει στη δωρεάν συνάρτηση getter της ιδιότητας |
| pSetter | void(*)(T) | Δείκτης συνάρτησης που δείχνει στη δωρεάν συνάρτηση setter της ιδιότητας |

### Τιμή Επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) συνάρτηση

Ο μεταφραστής μεταφράζει τις προ-απενεργοποιήσεις του C# που στοχεύουν σε ιδιότητα αντικειμένου που έχει ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης (υπερφόρτωση για μη-σταθερό getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας. |
| Host | - κλάση του αντικειμένου που θα τροποποιηθεί |
| HostGet | - Το Host ίδιο, ή ο βασικός του τύπος, όπου ορίζεται το getter της ιδιότητας |
| HostSet | - Το Host ίδιο, ή ο βασικός του τύπος, όπου ορίζεται το setter της ιδιότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | Host *const | Αντικείμενο για κλήση των getters και setters. |
| pGetter | T(HostGet::*)() | Δείκτης συνάρτησης που δείχνει στη συνάρτηση getter της ιδιότητας |
| pSetter | void(HostSet::*)(T) | Δείκτης συνάρτησης που δείχνει στη συνάρτηση setter της ιδιότητας |

### Τιμή Επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) συνάρτηση

Ο μεταφραστής μεταφράζει τις προ-απενεργοποιήσεις του C# που στοχεύουν σε ιδιότητα αντικειμένου που έχει ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης (υπερφόρτωση για σταθερό getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας. |
| Host | - κλάση του αντικειμένου που θα τροποποιηθεί |
| HostConstGet | - Το Host ίδιο, ή ο βασικός του τύπος, όπου ορίζεται το getter της ιδιότητας |
| HostSet | - Το Host ίδιο, ή ο βασικός του τύπος, όπου ορίζεται το setter της ιδιότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | Host *const | Αντικείμενο για κλήση των getters και setters. |
| pGetter | T(HostConstGet::*)() const | Δείκτης συνάρτησης που δείχνει στη συνάρτηση getter της ιδιότητας |
| pSetter | void(HostSet::*)(T) | Δείκτης συνάρτησης που δείχνει στη συνάρτηση setter της ιδιότητας |

### Τιμή Επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)