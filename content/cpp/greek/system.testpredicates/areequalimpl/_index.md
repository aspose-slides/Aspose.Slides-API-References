---
title: AreEqualImpl()
second_title: Aspose.Slides για C++ API Αναφορά
description: Συγκρίνει ισότητα αριθμητικών κινητών υποδιαστολής με αριθμητικούς τύπους.
type: docs
weight: 27
url: /el/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) συνάρτηση

Συγκρίνει ισότητα αριθμητικών κινητών υποδιαστολής με αριθμητικούς τύπους.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος αντικειμένου LHS. |
| T2 | Τύπος αντικειμένου RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1 | Τιμή LHS. |
| rhs | const T2 | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση

Συγκρίνει ισότητα τιμών, μία ή και οι δύο από τις οποίες είναι [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος αντικειμένου LHS. |
| T2 | Τύπος αντικειμένου RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) συνάρτηση

Συγκρίνει ισότητα τύπων μη-δείκτη χρησιμοποιώντας τη μέθοδο Equals που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) συνάρτηση

Συγκρίνει ισότητα τύπων μη-δείκτη χρησιμοποιώντας τη μέθοδο Equals που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) συνάρτηση

Συγκρίνει ισότητα τύπων μη-δείκτη χρησιμοποιώντας τον τελεστή == που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) συνάρτηση

Συγκρίνει ισότητα τύπων που μπορούν να τοποθετηθούν σε κουτί με τιμές [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T | Τιμή LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) συνάρτηση

Συγκρίνει ισότητα τύπων που μπορούν να τοποθετηθούν σε κουτί με τιμές [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Τιμή LHS. |
| rhs | T | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) συνάρτηση

Συγκρίνει ισότητα κυριολεξίας συμβολοσειράς με τιμές [SmartPtr](../../system/smartptr/) χρησιμοποιώντας αποσυσκευασία.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const char16_t * | Τιμή LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) συνάρτηση

Συγκρίνει ισότητα κυριολεξίας συμβολοσειράς με τιμές [SmartPtr](../../system/smartptr/) χρησιμοποιώντας αποσυσκευασία.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Τιμή LHS. |
| rhs | const char16_t * | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) συνάρτηση

Συγκρίνει ισότητα τυχαίου τύπου με nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T | Τιμή LHS. |
| s | std::nullptr_t | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) συνάρτηση

Συγκρίνει ισότητα τυχαίου τύπου με nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| rhs | std::nullptr_t | Τιμή RHS. |
| s | T | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) συνάρτηση

Συγκρίνει ισότητα τύπων δείκτη.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) συνάρτηση

Συγκρίνει ισότητα τύπων δείκτη.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) συνάρτηση

Συγκρίνει ισότητα τυχαίου τύπου με μια τιμή [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T1 | Τιμή LHS. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) συνάρτηση

Συγκρίνει ισότητα μιας τιμής [Nullable](../../system/nullable/) με τυχαίο τύπο.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | Τιμή LHS. |
| rhs | T2 | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) συνάρτηση

Συγκρίνει ισότητα τυχαίων τύπων χρησιμοποιώντας αλγόριθμους gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T1 | Τιμή LHS. |
| rhs | T2 | Τιμή RHS. |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) συνάρτηση

Συγκρίνει ισότητα δύο τιμών [System::String](../../system/string/), προστατεύοντας από την κλήση μιας μεθόδου μέλους σε ένα null [String](../../system/string/). Με πρότυπο (αντί για απλή υπερφόρτωση που δέχεται const [String](../../system/string/)&) ώστε οι κλήσεις μικτής τύπων - π.χ. μια κυριολεξία συμβολοσειράς char16_t που συγκρίνεται με ένα [String](../../system/string/) - να αποτυγχάνουν να προσδιορίσουν ένα ενιαίο συνεπές T και να αποκλειστούν εντελώς από αυτόν τον υποψήφιο, αντί να ανταγωνίζονται με το γενικό AreEqualImpl<T1,T2> μέσω της παραμέτρου επιλογέα long long/int και να προκαλούν ασάφεια στην ανάλυση υπερφόρτωσης.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../system/object/), περιορισμένο σε [System::String](../../system/string/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μία παράμετρος υπηρεσίας που χρησιμεύει ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

Αποτέλεσμα ισχυρισμού σε στυλ gtest.

## Δείτε επίσης

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Κλάση [String](../../system/string/)
* Κλάση [Object](../../system/object/)
* Κλάση [Stream](../../system.io/stream/)
* Κλάση [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Χώρος ονομάτων [System::TestPredicates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)