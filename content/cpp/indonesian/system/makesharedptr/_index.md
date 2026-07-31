---
title: MakeSharedPtr()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengonversi pointer mentah menjadi smart pointer.
type: docs
weight: 2900
url: /id/system/makesharedptr/
---
## System::MakeSharedPtr(X *) fungsi

Mengonversi pointer mentah menjadi smart pointer.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe pointee. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | X * | Pointer mentah ke objek. |

### Nilai Kembalian

Smart pointer bersama ke objek.

## System::MakeSharedPtr(const X *) fungsi

Mengonversi pointer mentah menjadi smart pointer. Overload untuk pointer const. Berguna misalnya ketika menggunakan variabel 'this' dalam metode C# yang diterjemahkan sebagai const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| X | Tipe pointee. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | const X * | Pointer mentah ke objek. |

### Nilai Kembalian

Smart pointer bersama ke objek.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)