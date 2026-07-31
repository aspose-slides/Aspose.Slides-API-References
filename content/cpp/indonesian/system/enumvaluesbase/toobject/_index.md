---
title: ToObject()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai bilangan bulat tak bertanda 64-bit yang ditentukan menjadi anggota enumerasi.
type: docs
weight: 40
url: /id/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) metode

Mengonversi nilai bilangan bulat tak bertanda 64-bit yang ditentukan menjadi anggota enumerasi.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Tipe enumerasi yang akan dikembalikan. |
| value | **uint64_t** | Nilai yang akan dikonversi menjadi anggota enumerasi. |

### Nilai Kembali

Sebuah instance dari enumerasi yang diatur ke nilai.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) metode

Mengonversi objek yang ditentukan dengan nilai bilangan bulat menjadi anggota enumerasi.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Tipe enumerasi yang akan dikembalikan. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Nilai yang dikonversi menjadi anggota enumerasi. |

### Nilai Kembali

Objek enumerasi yang nilainya adalah value.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Object](../../object/)
* Kelas [TypeInfo](../../typeinfo/)
* Kelas [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)