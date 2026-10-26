---
title: setter_post_decrement_wrap()
second_title: Referensi API Aspose.Slides untuk C++
description: Penerjemah menerjemahkan ekspresi post-decrement C# yang menargetkan properti kelas yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini.
type: docs
weight: 2874
url: /id/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) fungsi

Penerjemah menerjemahkan ekspresi post-decrement C# yang menargetkan properti kelas yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe properti |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pGetter | T(*)() | Pointer fungsi yang menunjuk ke fungsi bebas getter properti |
| pSetter | void(*)(T) | Pointer fungsi yang menunjuk ke fungsi bebas setter properti |

### Nilai Kembali

Nilai properti sebelum peningkatan

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) fungsi

Penerjemah menerjemahkan ekspresi post-decrement C# yang menargetkan properti instance yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini (overload untuk getter non-const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe properti. |
| Host | - kelas dari instance yang akan dimodifikasi |
| HostGet | - Host itu sendiri, atau tipe dasarnya, tempat getter properti didefinisikan |
| HostSet | - Host itu sendiri, atau tipe dasarnya, tempat setter properti didefinisikan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | Host *const | Instance untuk memanggil getter dan setter. |
| pGetter | T(HostGet::*)() | Pointer fungsi yang menunjuk ke fungsi getter properti |
| pSetter | void(HostSet::*)(T) | Pointer fungsi yang menunjuk ke fungsi setter properti |

### Nilai Kembali

Nilai properti sebelum peningkatan

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) fungsi

Penerjemah menerjemahkan ekspresi post-decrement C# yang menargetkan properti instance yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini (overload untuk getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe properti. |
| Host | - kelas dari instance yang akan dimodifikasi |
| HostConstGet | - Host itu sendiri, atau tipe dasarnya, tempat getter properti didefinisikan |
| HostSet | - Host itu sendiri, atau tipe dasarnya, tempat setter properti didefinisikan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | Host *const | Instance untuk memanggil getter dan setter. |
| pGetter | T(HostConstGet::*)() const | Pointer fungsi yang menunjuk ke fungsi getter properti |
| pSetter | void(HostSet::*)(T) | Pointer fungsi yang menunjuk ke fungsi setter properti |

### Nilai Kembali

Nilai properti sebelum peningkatan

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)