---
title: MakeObject()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek di heap dan mengembalikan pointer bersama ke objek tersebut.
type: docs
weight: 2887
url: /id/system/makeobject/
---
## System::MakeObject(Args\&&...) fungsi


Membuat objek di heap dan mengembalikan pointer bersama ke objek tersebut.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Kelas untuk diinstansiasi. |
| Args | Tipe argumen konstruktor. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | Args\&&... | Argumen konstruktor. |

### Nilai Kembali

[SmartPtr](../smartptr/) ke objek yang baru dibuat, selalu dalam mode berbagi.

## System::MakeObject(Args\&&...) fungsi


Membuat objek di heap dan mengembalikan pointer bersama ke objek tersebut.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [SmartPtr](../smartptr/) ke kelas untuk diinstansiasi. |
| Args | Tipe argumen konstruktor. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | Args\&&... | Argumen konstruktor. |

### Nilai Kembali

[SmartPtr](../smartptr/) ke objek yang baru dibuat, selalu dalam mode berbagi.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Struktur [IsSmartPtr](../issmartptr/)
* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)