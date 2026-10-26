---
title: AreSameImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: Bandingkan smart pointer untuk memeriksa kesamaan.
type: docs
weight: 79
url: /id/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) fungsi

Bandingkan smart pointer untuk memeriksa kesamaan.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe objek LHS. |
| T2 | Tipe objek RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T1\& | Nilai LHS. |
| rhs | const T2\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) fungsi

Bandingkan pengecualian untuk memeriksa kesamaan.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe objek LHS. |
| T2 | Tipe objek RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T1\& | Nilai LHS. |
| rhs | const T2\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) fungsi

Bandingkan nilai non-pointer untuk memeriksa kesamaan.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe objek LHS. |
| T2 | Tipe objek RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T1\& | Nilai LHS. |
| rhs | const T2\& | Nilai RHS. |

### Nilai Kembali

hasil asersi bergaya gtest.

## Lihat Juga

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)