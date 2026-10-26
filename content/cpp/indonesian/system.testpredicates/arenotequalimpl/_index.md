---
title: AreNotEqualImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: Tidak-sama membandingkan nilai satu atau keduanya yang bertipe Decimal.
type: docs
weight: 53
url: /id/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fungsi


Tidak-sama membandingkan nilai satu atau keduanya [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe objek LHS. |
| T2 | tipe objek RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T1\& | nilai LHS. |
| rhs | const T2\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) fungsi


Tidak-sama membandingkan dua nilai [System::String](../../system/string/), melindungi dari pemanggilan fungsi anggota pada [String](../../system/string/) null. Ditemplatkan untuk alasan pengecualian berbasis deduksi yang sama seperti overload AreEqualImpl [String](../../system/string/) di atas.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe, terbatas pada [System::String](../../system/string/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T\& | nilai LHS. |
| rhs | const T\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) fungsi


Tidak-sama membandingkan tipe non-pointer menggunakan metode Equals yang disediakan.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T\& | nilai LHS. |
| rhs | const T\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) fungsi


Tidak-sama membandingkan tipe non-pointer menggunakan metode Equals yang disediakan.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T\& | nilai LHS. |
| rhs | const T\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) fungsi


Tidak-sama membandingkan tipe non-pointer menggunakan operator != yang disediakan.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T\& | nilai LHS. |
| rhs | const T\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) fungsi


Tidak-sama membandingkan yang dapat dibungkus dengan nilai [SmartPtr](../../system/smartptr/) menggunakan unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T | nilai LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) fungsi


Tidak-sama membandingkan yang dapat dibungkus dengan nilai [SmartPtr](../../system/smartptr/) menggunakan unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | nilai LHS. |
| rhs | T | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) fungsi


Tidak-sama membandingkan tipe acak dengan nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T | nilai LHS. |
| s | std::nullptr_t | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) fungsi


Tidak-sama membandingkan tipe acak dengan nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| rhs | std::nullptr_t | nilai RHS. |
| s | T | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fungsi


Equal-membandingkan tipe pointer.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe LHS. |
| T2 | tipe RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T1\& | nilai LHS. |
| rhs | const T2\& | nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembali

hasil asersi bergaya gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) fungsi


Equal-membandingkan tipe acak menggunakan algoritma gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe LHS. |
| T2 | tipe RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T1 | nilai LHS. |
| rhs | T2 | nilai RHS. |

### Nilai Kembali

hasil asersi bergaya gtest.

## Lihat Juga

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)