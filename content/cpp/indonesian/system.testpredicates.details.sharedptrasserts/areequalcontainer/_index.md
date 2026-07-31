---
title: AreEqualContainer()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan dua kontainer menggunakan operator == pada elemen. Berfungsi untuk elemen non-SmartPtr.
type: docs
weight: 1
url: /id/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) fungsi

Membandingkan dua kontainer menggunakan operator == pada elemen. Berfungsi untuk elemen non-SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe kontainer LHS. |
| T2 | Tipe kontainer RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | const T1\& | Kontainer LHS. |
| rhs | const T2\& | Kontainer RHS. |

### Nilai Kembalian

Benar jika elemen yang terkandung dan ukuran cocok, salah jika tidak.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) fungsi

Membandingkan dua kontainer menggunakan [System::Object::Equals](../../system/object/equals/) pada elemen. Berfungsi untuk elemen [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe kontainer LHS. |
| T2 | Tipe kontainer RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | const T1\& | Referensi kontainer LHS. |
| rhs | const T2\& | Referensi kontainer RHS. |

### Nilai Kembalian

Benar jika elemen yang terkandung dan ukuran cocok, salah jika tidak.

## Lihat Juga

* Struct [IsSmartPtr](../../system/issmartptr/)
* Ruang Nama [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)