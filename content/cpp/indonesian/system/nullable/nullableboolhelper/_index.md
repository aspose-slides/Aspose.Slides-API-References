---
title: NullableBoolHelper()
second_title: Referensi API Aspose.Slides untuk C++
description: Fungsi pembantu untuk memeriksa apakah this dan other keduanya tidak null dan memanggil lambda jika demikian. Digunakan dalam implementation.s.
type: docs
weight: 105
url: /id/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

Fungsi pembantu untuk memeriksa apakah **this** dan **other** keduanya tidak null dan memanggil lambda jika demikian. Digunakan dalam implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nullable lain. |

### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | Nilai nullable lain untuk dibandingkan. |
| f | const std::function\<**bool**()>\& | Lambda yang dipanggil jika **this** dan **other** keduanya tidak null. |
| default_if_both_are_null | **bool** | Nilai kembali jika kedua nilai null. |

### Nilai Kembalian

false jika **this** atau **other** null; **default_if_both_are_null** jika keduanya null; hasil panggilan **f** jika keduanya tidak null.

## Lihat Juga

* Kelas [Nullable](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)