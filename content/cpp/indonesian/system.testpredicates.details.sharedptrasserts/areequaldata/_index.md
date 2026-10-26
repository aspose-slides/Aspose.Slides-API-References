---
title: AreEqualData()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membandingkan dua kontainer secara equal menggunakan System::Object::Equals pada elemen. Berfungsi untuk elemen SmartPtr."
type: docs
weight: 14
url: /id/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) fungsi

Membandingkan dua kontainer secara equal menggunakan [System::Object::Equals](../../system/object/equals/) pada elemen. Berfungsi untuk elemen [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe kontainer LHS. |
| T2 | tipe kontainer RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | const T1\& | referensi kontainer LHS. |
| rhs | const T2\& | referensi kontainer RHS. |

### Nilai Kembalian

Benar jika elemen yang terkandung dan ukuran cocok, false otherwise.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) fungsi

Membandingkan dua kontainer secara equal menggunakan operator == pada elemen. Berfungsi untuk elemen non-SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe kontainer LHS. |
| T2 | tipe kontainer RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | const T1\& | kontainer LHS. |
| rhs | const T2\& | kontainer RHS. |

### Nilai Kembalian

Benar jika elemen yang terkandung dan ukuran cocok, false otherwise.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) fungsi

Membandingkan dua kontainer dengan tipe identik secara equal. Berfungsi untuk elemen non-SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | tipe kontainer LHS. |
| T2 | tipe kontainer RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | const T\& | kontainer LHS. |
| rhs | const T\& | kontainer RHS. |

### Nilai Kembalian

Benar jika elemen yang terkandung dan ukuran cocok, false otherwise.

## Lihat Juga

* Struktur [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Pustaka [Aspose.Slides](../../)