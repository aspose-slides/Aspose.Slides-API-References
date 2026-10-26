---
title: NotNullAreNotEqualImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: Perbandingan tidak sama pada array atau daftar.
type: docs
weight: 105
url: /id/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fungsi


Perbandingan tidak sama pada array atau daftar.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe kontainer LHS. |
| T2 | tipe kontainer RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | ekspresi LHS. |
| rhs_expr | const char * | ekspresi RHS. |
| lhs | const T1\& | nilai LHS. |
| rhs | const T2\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fungsi


Perbandingan tidak sama pada instance IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe elemen LHS. |
| T2 | tipe elemen RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | ekspresi LHS. |
| rhs_expr | const char * | ekspresi RHS. |
| lhs | const T1\& | nilai LHS. |
| rhs | const T2\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) fungsi


Perbandingan tidak sama pada tipe yang tidak diketahui menggunakan metode Eqauals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe objek LHS. |
| T2 | tipe objek RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | ekspresi LHS. |
| rhs_expr | const char * | ekspresi RHS. |
| lhs | const T1\& | nilai LHS. |
| rhs | const T2\& | nilai RHS. |

### Nilai Kembalian

hasil asersi bergaya gtest.

## Lihat Juga

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Ruang Nama [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)