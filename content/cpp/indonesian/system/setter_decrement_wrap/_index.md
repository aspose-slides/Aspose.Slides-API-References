---
title: setter_decrement_wrap()
second_title: Referensi API Aspose.Slides untuk C++
description: Penerjemah menerjemahkan ekspresi pre-decrement C# yang menargetkan properti kelas yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini.
type: docs
weight: 2861
url: /id/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) fungsi

Penerjemah menerjemahkan ekspresi pre-decrement C# yang menargetkan properti kelas yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe properti |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pGetter | T(*)() | Penunjuk fungsi yang mengarah ke fungsi bebas getter properti |
| pSetter | void(*)(T) | Penunjuk fungsi yang mengarah ke fungsi bebas setter properti |

### Nilai Kembali

Nilai properti sebelum diinkrementasi

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) fungsi

Penerjemah menerjemahkan ekspresi pre-decrement C# yang menargetkan properti instance yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini (overload untuk getter non-const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe properti. |
| Host | - kelas instance yang akan dimodifikasi |
| HostGet | - Host itu sendiri, atau tipe dasarnya, tempat getter properti didefinisikan |
| HostSet | - Host itu sendiri, atau tipe dasarnya, tempat setter properti didefinisikan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | Host *const | Instance untuk memanggil getter dan setter. |
| pGetter | T(HostGet::*)() | Penunjuk fungsi yang mengarah ke fungsi getter properti |
| pSetter | void(HostSet::*)(T) | Penunjuk fungsi yang mengarah ke fungsi setter properti |

### Nilai Kembali

Nilai properti sebelum diinkrementasi

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) fungsi

Penerjemah menerjemahkan ekspresi pre-decrement C# yang menargetkan properti instance yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini (overload untuk getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe properti. |
| Host | - kelas instance yang akan dimodifikasi |
| HostConstGet | - Host itu sendiri, atau tipe dasarnya, tempat getter properti didefinisikan |
| HostSet | - Host itu sendiri, atau tipe dasarnya, tempat setter properti didefinisikan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | Host *const | Instance untuk memanggil getter dan setter. |
| pGetter | T(HostConstGet::*)() const | Penunjuk fungsi yang mengarah ke fungsi getter properti |
| pSetter | void(HostSet::*)(T) | Penunjuk fungsi yang mengarah ke fungsi setter properti |

### Nilai Kembali

Nilai properti sebelum diinkrementasi

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)