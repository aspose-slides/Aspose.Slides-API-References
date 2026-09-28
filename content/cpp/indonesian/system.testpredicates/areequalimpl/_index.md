---
title: AreEqualImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan nilai floating point dengan tipe aritmetika secara setara.
type: docs
weight: 27
url: /id/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) function

Membandingkan nilai floating point dengan tipe aritmetika.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
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
| lhs | const T1 | Nilai LHS. |
| rhs | const T2 | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Membandingkan nilai satu atau keduanya yang merupakan [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| lhs | const T1\& | Nilai LHS. |
| rhs | const T2\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Membandingkan tipe non-pointer menggunakan metode Equals yang disediakan.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe [Object](../../system/object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T\& | Nilai LHS. |
| rhs | const T\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) function

Membandingkan tipe non-pointer menggunakan metode Equals yang disediakan.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe [Object](../../system/object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T\& | Nilai LHS. |
| rhs | const T\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Membandingkan tipe non-pointer menggunakan operator == yang disediakan.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe [Object](../../system/object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T\& | Nilai LHS. |
| rhs | const T\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

Membandingkan tipe boxable dengan nilai [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe [Object](../../system/object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T | Nilai LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

Membandingkan tipe boxable dengan nilai [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe [Object](../../system/object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Nilai LHS. |
| rhs | T | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) function

Membandingkan literal string dengan nilai [SmartPtr](../../system/smartptr/) menggunakan unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const char16_t * | Nilai LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) function

Membandingkan literal string dengan nilai [SmartPtr](../../system/smartptr/) menggunakan unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Nilai LHS. |
| rhs | const char16_t * | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Membandingkan tipe acak dengan nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe [Object](../../system/object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | T | Nilai LHS. |
| s | std::nullptr_t | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Membandingkan tipe acak dengan nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe [Object](../../system/object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| rhs | std::nullptr_t | Nilai RHS. |
| s | T | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Membandingkan tipe pointer.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| lhs | const T1\& | Nilai LHS. |
| rhs | const T2\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Membandingkan tipe pointer.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| lhs | const T1\& | Nilai LHS. |
| rhs | const T2\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) function

Membandingkan tipe acak dengan nilai [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
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
| lhs | T1 | Nilai LHS. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) function

Membandingkan nilai [Nullable](../../system/nullable/) dengan tipe acak.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
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
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | Nilai LHS. |
| rhs | T2 | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) function

Membandingkan tipe acak menggunakan algoritma gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
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
| lhs | T1 | Nilai LHS. |
| rhs | T2 | Nilai RHS. |

### Nilai Kembalian

hasil asersi bergaya gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Membandingkan dua nilai [System::String](../../system/string/), melindungi dari pemanggilan fungsi anggota pada [String](../../system/string/) null. Templated (bukan overload biasa yang mengambil const [String](../../system/string/)&) sehingga pemanggilan tipe campuran – misalnya literal string char16_t dibandingkan dengan [String](../../system/string/) – gagal mendeteksi T konsisten tunggal dan dikeluarkan dari kandidat ini sepenuhnya, alih-alih bersaing dengan template AreEqualImpl<T1,T2> melalui parameter pemilih long long/int dan menghasilkan resolusi overload ambigu.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe [Object](../../system/object/), dibatasi pada [System::String](../../system/string/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs_expr | const char * | Ekspresi LHS. |
| rhs_expr | const char * | Ekspresi RHS. |
| lhs | const T\& | Nilai LHS. |
| rhs | const T\& | Nilai RHS. |
| s | long long | Parameter layanan yang berfungsi sebagai pemilih implementasi fungsi; nilai parameter diabaikan |

### Nilai Kembalian

hasil asersi bergaya gtest.

## Lihat Juga

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Kelas [String](../../system/string/)
* Kelas [Object](../../system/object/)
* Kelas [Stream](../../system.io/stream/)
* Kelas [Nullable](../../system/nullable/)
* Struktur [IsSmartPtr](../../system/issmartptr/)
* Struktur [IsBoxable](../../system/isboxable/)
* Struktur [IsStringByteSequence](../../system/isstringbytesequence/)
* Struktur [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Pustaka [Aspose.Slides](../../)