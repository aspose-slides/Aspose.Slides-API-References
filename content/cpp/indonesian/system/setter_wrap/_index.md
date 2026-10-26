---
title: setter_wrap()
second_title: Referensi API Aspose.Slides untuk C++
description: Overload untuk fungsi setter statis dengan konversi tipe.
type: docs
weight: 2822
url: /id/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) fungsi

Overload untuk fungsi setter statis dengan konversi tipe.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai. |
| T2 | Tipe yang diharapkan oleh fungsi setter. |

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| pSetter | void(*)(T2) | Referensi fungsi setter statis. |
| value | T | Nilai untuk diatur. |

### Nilai Kembalian

menetapkan nilai.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) fungsi

Overload untuk fungsi setter instance dengan konversi tipe.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai. |
| T2 | Tipe yang diharapkan oleh fungsi setter. |
| Host | Tipe instance. |
| HostSet | - Host itu sendiri, atau tipe dasarnya, tempat setter properti didefinisikan. |

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| host | Host *const | [Object](../object/) untuk memanggil fungsi setter bagi. |
| pSetter | void(HostSet::*)(T2) | Referensi fungsi setter. |
| value | T | Nilai untuk diatur. |

### Nilai Kembalian

menetapkan nilai.

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)