---
title: setter_increment_wrap()
second_title: Aspose.Slides for C++ Referensi API
description: Penerjemah menerjemahkan ekspresi increment C# yang menargetkan properti kelas yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini.
type: docs
weight: 2835
url: /id/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) fungsi


Penerjemah menerjemahkan ekspresi increment C# yang menargetkan properti kelas yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
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

Nilai properti yang diinkrementasi

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) fungsi


Penerjemah menerjemahkan ekspresi increment C# yang menargetkan properti kelas yang memiliki setter dan getter yang didefinisikan, menjadi pemanggilan fungsi ini.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe properti |
| Host | - kelas dari instance yang akan dimodifikasi |
| HostGet | - Host itu sendiri, atau tipe dasarnya, tempat getter properti didefinisikan |
| HostSet | - Host itu sendiri, atau tipe dasarnya, tempat setter properti didefinisikan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | Host *const | Pointer ke objek yang propertinya akan diinkrementasi |
| pGetter | T(HostGet::*)() | Pointer fungsi yang menunjuk ke metode getter properti |
| pSetter | void(HostSet::*)(T) | Pointer fungsi yang menunjuk ke metode setter properti |

### Nilai Kembali

Nilai properti yang diinkrementasi

## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)