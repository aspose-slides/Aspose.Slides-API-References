---
title: GetCustomAttributes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah array yang berisi objek yang mewakili semua atribut khusus yang diterapkan pada tipe yang diwakili oleh objek saat ini.
type: docs
weight: 66
url: /id/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const metode


Mengembalikan sebuah array yang berisi objek yang mewakili semua atribut khusus yang diterapkan pada tipe yang diwakili oleh objek saat ini.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Tipe atribut yang akan dicari. |
| inherit | **bool** | Apakah juga memeriksa atribut yang diwariskan. |

## MemberInfo::GetCustomAttributes(bool) const metode


Mengembalikan sebuah array yang berisi objek yang mewakili semua atribut khusus yang diterapkan pada tipe yang diwakili oleh objek saat ini.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inherit | **bool** | Apakah juga memeriksa atribut yang diwariskan. |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [MemberInfo](../)
* Ruang Nama [System::Reflection](../../)
* Perpustakaan [Aspose.Slides](../../../)