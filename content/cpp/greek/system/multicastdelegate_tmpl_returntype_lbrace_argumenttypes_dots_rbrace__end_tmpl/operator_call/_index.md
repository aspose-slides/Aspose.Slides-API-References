---
title: operator()()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καλεί όλα τα delegates που είναι αυτή τη στιγμή στη συλλογή των delegates. Τα delegates κλήνονται με την ίδια σειρά όπως προστέθηκαν στη συλλογή. Ο τελεστής μπλοκάρει ενώ τα delegates εκτελούνται.
type: docs
weight: 235
url: /el/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const method


Καλεί όλα τα delegates που υπάρχουν αυτή τη στιγμή στη συλλογή των delegates. Τα delegates κλήθηκαν με την ίδια σειρά με την οποία προστέθηκαν στη συλλογή. Ο τελεστής αποκλείει την εκτέλεση ενώ τα delegates εκτελούνται.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | ArgumentTypes... | Ορίσματα που θα περαστούν στα delegates προς κλήση |

### Τιμή επιστροφής

Τιμή επιστροφής του τελευταίου delegate που κλήθηκε

## Δείτε επίσης

* Κλάση [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)