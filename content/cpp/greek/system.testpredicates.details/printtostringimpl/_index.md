---
title: PrintToStringImpl()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Εκτυπώνει την υποκατηγορία System::Object σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο ToString()."
type: docs
weight: 14
url: /el/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) συνάρτηση

Εκτυπώνει την υποκατηγορία [System::Object](../../system/object/) σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τελικός τύπος κλάσης. |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Δείκτης στο αντικείμενο για εκτύπωση. |
| s | long long | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

[String](../../system/string/) αναπαράσταση του αντικειμένου που περάστηκε ή "nullptr", εάν **value** είναι null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) συνάρτηση

Εκτυπώνει την υποκατηγορία [System::Object](../../system/object/) σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τελικός τύπος κλάσης. |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Δείκτης στο αντικείμενο για εκτύπωση. |
| s | long long | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

[String](../../system/string/) αναπαράσταση του αντικειμένου που περάστηκε ή "nullptr", εάν **value** είναι null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) συνάρτηση

Εκτυπώνει το αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) προς εκτύπωση. |
| s | long long | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

[String](../../system/string/) αναπαράσταση του αντικειμένου που περάστηκε.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) συνάρτηση

Εκτυπώνει το αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) προς εκτύπωση. |
| s | long long | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

[String](../../system/string/) αναπαράσταση του αντικειμένου που περάστηκε.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) συνάρτηση

Εκτυπώνει το αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) προς εκτύπωση. |
| s | long long | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

[String](../../system/string/) αναπαράσταση του αντικειμένου που περάστηκε.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) συνάρτηση

Εκτυπώνει το ζεύγος σε συμβολοσειρά.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Πρώτος τύπος του ζεύγους. |
| T2 | Δεύτερος τύπος του ζεύγους. |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) προς εκτύπωση. |
| s | long long | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

Συγγενικές αναπαραστάσεις συμβολοσειράς των πρώτων και δεύτερων στοιχείων του ζεύγους.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) συνάρτηση

Εκτυπώνει το ζεύγος σε συμβολοσειρά.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Πρώτος τύπος του ζεύγους. |
| T2 | Δεύτερος τύπος του ζεύγους. |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) προς εκτύπωση. |
| s | long long | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

Συγγενικές αναπαραστάσεις συμβολοσειράς των πρώτων και δεύτερων στοιχείων του ζεύγους.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) συνάρτηση

Εκτυπώνει κοντέινερ τύπου STL σε συμβολοσειρά εκτυπώνοντας τα στοιχεία τους (όχι περισσότερα από 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) προς εκτύπωση. |
| s | long long | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

Συγγενικές αναπαραστάσεις συμβολοσειράς των στοιχείων που περιέχονται.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) συνάρτηση

Εκτυπώνει άλλους τύπους σε συμβολοσειρά χρησιμοποιώντας συναρτήσεις που παρέχονται από το gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) προς εκτύπωση. |
| s | int | Μία παράμετρος υπηρεσίας η οποία λειτουργεί ως επιλογέας υπερφόρτωσης της συνάρτησης βάσει του τύπου αυτής της παραμέτρου· η τιμή της παραμέτρου αγνοείται |

### Return Value

[String](../../system/string/) αναπαραστάσεις του αντικειμένου που περάστηκε.

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Κλάση [WeakPtr](../../system/weakptr/)
* Κλάση [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Κλάση [Object](../../system/object/)
* Δομή [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Δομή [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Δομή [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Χώρος ονομάτων [System::TestPredicates::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)