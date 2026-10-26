---
title: EnumValues
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan informasi meta tentang konstanta enumerasi dari tipe enum E.
type: docs
weight: 794
url: /id/system/enumvalues/
---
## EnumValues kelas

Menyediakan informasi meta tentang konstanta enumerasi dari tipe enum **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| E | Tipe enumerasi |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Membuat sebuah instance. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Mengembalikan sebuah array yang berisi semua nama enumerasi **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Mengambil sebuah array berisi nama-nama konstanta dalam enumerasi yang ditentukan. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Mengembalikan tipe dasar dari enumerasi yang ditentukan. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Mengembalikan tipe dasar dari enumerasi yang ditentukan. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Mengembalikan nilai terbungkus dari konstanta enum dengan nama yang ditentukan. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Mengembalikan nilai terbungkus dari konstanta enum dengan nilai yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Mengembalikan sebuah array yang berisi semua nilai enumerasi **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Mengembalikan sebuah array yang berisi semua nilai dari tipe enumerasi yang ditentukan. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Mengembalikan sebuah objek yang mewakili nilai dari konstanta enumerasi tipe yang ditentukan dengan nama yang ditentukan. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Mengonversi nilai bilangan bulat tak bertanda 64-bit yang ditentukan menjadi anggota enumerasi. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Mengonversi objek yang ditentukan dengan nilai integer menjadi anggota enumerasi. |
| virtual  [~EnumValues](./~enumvalues/)() | Penghancur. |

## Lihat Juga

* Kelas [EnumValuesBase](../enumvaluesbase/)
* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)