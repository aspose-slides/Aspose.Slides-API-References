---
title: setter_wrap()
second_title: Αναφορά API Aspose.Slides για C++
description: Υπερφόρτωση για στατικές συναρτήσεις setter με μετατροπή τύπου.
type: docs
weight: 2783
url: /el/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) συνάρτηση

Υπερφόρτωση για στατικές συναρτήσεις setter με μετατροπή τύπου.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος τιμής. |
| T2 | Τύπος που αναμένεται από τη συνάρτηση setter. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pSetter | void(*)(T2) | Αναφορά σε στατική συνάρτηση setter. |
| value | T | Τιμή για ρύθμιση. |

### Τιμή Επιστροφής

Τιμή που ορίζεται.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) συνάρτηση

Υπερφόρτωση για συναρτήσεις setter παραδείγματος με μετατροπή τύπου.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος τιμής. |
| T2 | Τύπος που αναμένεται από τη συνάρτηση setter. |
| Host | Τύπος παραδείγματος. |
| HostSet | - Ο ίδιος ο Host, ή ο βασικός του τύπος, όπου η setter της ιδιότητας ορίζεται. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | Host *const | [Object](../object/) για κλήση της συνάρτησης setter. |
| pSetter | void(HostSet::*)(T2) | Αναφορά σε συνάρτηση setter. |
| value | T | Τιμή για ρύθμιση. |

### Τιμή Επιστροφής

Τιμή που ορίζεται.

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)