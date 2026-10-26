---
title: AreNotSameImpl()
second_title: Aspose.Slides για την API αναφορά C++
description: Are-not-same συγκρίνει έξυπνους δείκτες.
type: docs
weight: 105
url: /el/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση

Are-not-same-compares έξυπνους δείκτες.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | Μία παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

gtest-styled αποτέλεσμα έγκρισης.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) συνάρτηση

Are-not-same-compares μη-δείκτη τιμές.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### Τιμή Επιστροφής

gtest-styled αποτέλεσμα έγκρισης.

## Δείτε επίσης

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)