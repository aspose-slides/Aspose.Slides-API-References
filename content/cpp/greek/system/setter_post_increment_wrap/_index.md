---
title: setter_post_increment_wrap()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Ο μεταφραστής μετατρέπει τις εκφράσεις μετά-αύξησης της C# που στοχεύουν στην ιδιότητα της κλάσης που έχει ορισμένους setter και getter, σε κλήση αυτής της συνάρτησης.
type: docs
weight: 2809
url: /el/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) συνάρτηση

Ο μεταφραστής μετατρέπει τις εκφράσεις μετά-αύξησης της C# που στοχεύουν στην ιδιότητα της κλάσης που έχει ορισμένους setter και getter, σε κλήση αυτής της συνάρτησης.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pGetter | T(*)() | Δείκτης συνάρτησης που δείχνει στη δωρεάν συνάρτηση getter της ιδιότητας |
| pSetter | void(*)(T) | Δείκτης συνάρτησης που δείχνει στη δωρεάν συνάρτηση setter της ιδιότητας |

### Τιμή Επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) συνάρτηση

Ο μεταφραστής μετατρέπει τις εκφράσεις μετά-αύξησης της C# που στοχεύουν στην ιδιότητα ενός αντικειμένου που έχει ορισμένους setter και getter, σε κλήση αυτής της συνάρτησης (υπερφόρτωση για μη-σταθερό getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας. |
| Host | - κλάση του αντικειμένου που θα τροποποιηθεί |
| HostGet | - ο ίδιος Host ή ο βασικός του τύπος, όπου ορίζεται ο getter της ιδιότητας |
| HostSet | - ο ίδιος Host ή ο βασικός του τύπος, όπου ορίζεται ο setter της ιδιότητας |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | Host *const | Αντικείμενο για το οποίο καλούνται οι getter και setter. |
| pGetter | T(HostGet::*)() | Δείκτης συνάρτησης που δείχνει στη συνάρτηση getter της ιδιότητας |
| pSetter | void(HostSet::*)(T) | Δείκτης συνάρτησης που δείχνει στη συνάρτηση setter της ιδιότητας |

### Τιμή Επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) συνάρτηση

Ο μεταφραστής μετατρέπει τις εκφράσεις μετά-αύξησης της C# που στοχεύουν στην ιδιότητα ενός αντικειμένου που έχει ορισμένους setter και getter, σε κλήση αυτής της συνάρτησης (υπερφόρτωση για const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος της ιδιότητας. |
| Host | - κλάση του αντικειμένου που θα τροποποιηθεί |
| HostConstGet | - ο ίδιος Host ή ο βασικός του τύπος, όπου ορίζεται ο const getter της ιδιότητας |
| HostSet | - ο ίδιος Host ή ο βασικός του τύπος, όπου ορίζεται ο setter της ιδιότητας |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | Host *const | Αντικείμενο για το οποίο καλούνται οι getter και setter. |
| pGetter | T(HostConstGet::*)() const | Δείκτης συνάρτησης που δείχνει στη συνάρτηση getter της ιδιότητας |
| pSetter | void(HostSet::*)(T) | Δείκτης συνάρτησης που δείχνει στη συνάρτηση setter της ιδιότητας |

### Τιμή Επιστροφής

Η τιμή της ιδιότητας πριν την αύξηση

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)