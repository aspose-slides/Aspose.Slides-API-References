---
title: setter_post_decrement_wrap()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ο μεταφραστής μεταφράζει τις εκφράσεις post-decrement της C# που στοχεύουν στην ιδιότητα της κλάσης με ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης.
type: docs
weight: 2835
url: /el/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) συνάρτηση

Ο μεταφραστής μεταφράζει τις εκφράσεις post-decrement της C# που στοχεύουν στην ιδιότητα της κλάσης με ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pGetter | T(*)() | Δείκτης συνάρτησης που δείχνει στη λειτουργία getter της ιδιότητας |
| pSetter | void(*)(T) | Δείκτης συνάρτησης που δείχνει στη λειτουργία setter της ιδιότητας |

### Τιμή επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) συνάρτηση

Ο μεταφραστής μεταφράζει τις εκφράσεις post-decrement της C# που στοχεύουν στην ιδιότητα του αντικειμένου με ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης (υπερφόρτωση για μη-const getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας. |
| Host | - κλάση του αντικειμένου που θα τροποποιηθεί |
| HostGet | - το ίδιο το Host ή τον τύπο βάσης του, όπου ορίζεται το getter της ιδιότητας |
| HostSet | - το ίδιο το Host ή τον τύπο βάσης του, όπου ορίζεται το setter της ιδιότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | Host *const | Αντικείμενο για το οποίο καλούνται getters και setters. |
| pGetter | T(HostGet::*)() | Δείκτης συνάρτησης που δείχνει στη λειτουργία getter της ιδιότητας |
| pSetter | void(HostSet::*)(T) | Δείκτης συνάρτησης που δείχνει στη λειτουργία setter της ιδιότητας |

### Τιμή επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) συνάρτηση

Ο μεταφραστής μεταφράζει τις εκφράσεις post-decrement της C# που στοχεύουν στην ιδιότητα του αντικειμένου με ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης (υπερφόρτωση για const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας. |
| Host | - κλάση του αντικειμένου που θα τροποποιηθεί |
| HostConstGet | - το ίδιο το Host ή τον τύπο βάσης του, όπου ορίζεται το getter της ιδιότητας |
| HostSet | - το ίδιο το Host ή τον τύπο βάσης του, όπου ορίζεται το setter της ιδιότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | Host *const | Αντικείμενο για το οποίο καλούνται getters και setters. |
| pGetter | T(HostConstGet::*)() const | Δείκτης συνάρτησης που δείχνει στη λειτουργία getter της ιδιότητας |
| pSetter | void(HostSet::*)(T) | Δείκτης συνάρτησης που δείχνει στη λειτουργία setter της ιδιότητας |

### Τιμή επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)