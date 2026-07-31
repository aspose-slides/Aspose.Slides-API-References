---
title: Nullable()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat sebuah instance yang merepresentasikan nilai null.
type: docs
weight: 1
url: /id/system/nullable/nullable/
---
## Nullable::Nullable() konstruktor

Membuat sebuah instance yang merepresentasikan nilai null.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) konstruktor

Membuat sebuah instance yang merepresentasikan null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) konstruktor

Membuat sebuah instance dari kelas [Nullable](../) yang merepresentasikan nilai yang ditentukan yang dikonversi (jika perlu) ke nilai dari tipe dasar T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe dari nilai yang ditentukan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T1\& | Sebuah referensi konstan ke nilai yang akan direpresentasikan oleh objek [Nullable](../) yang baru dibangun |

## Nullable::Nullable(const Nullable\<T1\>\&) konstruktor

Membuat sebuah instance yang merepresentasikan nilai yang direpresentasikan oleh objek [Nullable](../) yang ditentukan. Objek nullable yang ditentukan mungkin merepresentasikan nilai dengan tipe berbeda daripada tipe dasar instance yang dibangun, sehingga nilai yang direpresentasikan dikonversi ke nilai dengan tipe T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai yang direpresentasikan oleh objek [Nullable](../) yang ditentukan |

## Lihat Juga

* Kelas [Nullable](../)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)