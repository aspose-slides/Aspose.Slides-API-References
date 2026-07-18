---
title: setter_increment_wrap()
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: Ο Translator μετατρέπει τις εκφράσεις αύξησης της C# που στοχεύουν σε ιδιότητα κλάσης με ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης.
type: docs
weight: 2796
url: /el/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) συνάρτηση

Ο Translator μετατρέπει τις εκφράσεις αύξησης της C# που στοχεύουν στην ιδιότητα μιας κλάσης η οποία έχει ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Ο τύπος της ιδιότητας |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Δείκτης συνάρτησης που δείχνει στη δωρεάν συνάρτηση getter της ιδιότητας |
| pSetter | void(*)(T) | Δείκτης συνάρτησης που δείχνει στη δωρεάν συνάρτηση setter της ιδιότητας |

### Τιμή Επιστροφής

Η αυξημένη τιμή της ιδιότητας

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) συνάρτηση

Ο Translator μετατρέπει τις εκφράσεις αύξησης της C# που στοχεύουν στην ιδιότητα μιας κλάσης η οποία έχει ορισμένο setter και getter, σε κλήση αυτής της συνάρτησης.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Ο τύπος της ιδιότητας |
| Host | - κλάση του αντικειμένου που θα τροποποιηθεί |
| HostGet | - ο Host ο ίδιος, ή ο βασικός του τύπος, όπου ορίζεται ο getter της ιδιότητας |
| HostSet | - ο Host ο ίδιος, ή ο βασικός του τύπος, όπου ορίζεται ο setter της ιδιότητας |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Ένας δείκτης σε αντικείμενο του οποίου η ιδιότητα θα αυξηθεί |
| pGetter | T(HostGet::*)() | Δείκτης συνάρτησης που δείχνει στη μέθοδο getter της ιδιότητας |
| pSetter | void(HostSet::*)(T) | Δείκτης συνάρτησης που δείχνει στη μέθοδο setter της ιδιότητας |

### Τιμή Επιστροφής

Η αυξημένη τιμή της ιδιότητας

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)