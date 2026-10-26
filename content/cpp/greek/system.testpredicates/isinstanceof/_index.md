---
title: IsInstanceOf()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Η Is-instance-of συγκρίνει τα ορίσματα για τη μετάφραση της δήλωσης IsInstanceOf.
type: docs
weight: 118
url: /el/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) συνάρτηση


Η Is-instance-of συγκρίνει τα ορίσματα για τη μετάφραση της δήλωσης IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος ορίσματος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Ένα αντικείμενο typeInfo που αντιπροσωπεύει έναν τύπο έναντι του οποίου ο τύπος του **obj** συγκρίνεται |
| obj | const T\& | Ένα αντικείμενο του οποίου ο τύπος πρέπει να συγκριθεί με τον καθορισμένο τύπο |

### Τιμή επιστροφής

Αποτέλεσμα δήλωσης σε στυλ gtest.

## Δείτε επίσης

* Κλάση [TypeInfo](../../system/typeinfo/)
* Χώρος ονομάτων [System::TestPredicates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)