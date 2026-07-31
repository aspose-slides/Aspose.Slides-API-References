---
title: GetCustomAttributes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan array yang berisi objek-objek yang mewakili semua atribut khusus yang diterapkan pada tipe.
type: docs
weight: 586
url: /id/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const metode

Mengembalikan sebuah array yang berisi objek-objek yang mewakili semua atribut khusus yang diterapkan pada tipe.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```
## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const metode

Mengembalikan sebuah array yang berisi objek-objek yang mewakili atribut khusus tertentu yang diterapkan pada tipe.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Tipe atribut yang dicari. |
| inherit | **bool** | Apakah juga mencari atribut yang diwariskan. |

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [SmartPtr](../../smartptr/)
* Kelas [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)