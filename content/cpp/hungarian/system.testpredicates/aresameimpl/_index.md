---
title: AreSameImpl()
second_title: Aspose.Slides C++ API-referencia
description: Az Are-same összehasonlítja az okos mutatókat.
type: docs
weight: 79
url: /hu/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény

Are-same-compares okos mutatókat.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | LHS objektumtípus. |
| T2 | RHS objektumtípus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | const T1\& | LHS érték. |
| rhs | const T2\& | RHS érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Return Value

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény

Are-same-compares kivételeket.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | LHS objektumtípus. |
| T2 | RHS objektumtípus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | const T1\& | LHS érték. |
| rhs | const T2\& | RHS érték. |
| s | long long | Egy szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Return Value

gtest-stílusú állítási eredmény.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) függvény

Are-same-compares nem mutató értékeket.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | LHS objektumtípus. |
| T2 | RHS objektumtípus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | const T1\& | LHS érték. |
| rhs | const T2\& | RHS érték. |

### Return Value

gtest-stílusú állítási eredmény.

## Lásd még

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)