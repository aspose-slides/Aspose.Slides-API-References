---
title: operator=()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan null ke objek saat ini.
type: docs
weight: 14
url: /id/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) metode

Menetapkan null ke objek saat ini.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Nilai Kembali

Sebuah objek [Nullable](../) yang mewakili nilai null.

## Nullable::operator=(const T1\&) metode

Mengganti nilai yang saat ini direpresentasikan oleh objek dengan nilai yang ditentukan.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| The | tipe nilai baru yang akan direpresentasikan oleh objek saat ini |

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| x | const T1\& | Nilai baru yang akan direpresentasikan oleh objek saat ini |

### Nilai Kembali

Referensi ke diri sendiri

## Nullable::operator=(const Nullable\<T1\>\&) metode

Mengganti nilai yang saat ini direpresentasikan oleh objek dengan nilai yang ditentukan.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| The | tipe nilai baru yang akan direpresentasikan oleh objek saat ini |

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | Nilai baru yang akan direpresentasikan oleh objek saat ini |

### Nilai Kembali

Referensi ke diri sendiri

## Lihat Juga

* Kelas [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)