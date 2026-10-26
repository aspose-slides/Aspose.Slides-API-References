---
title: EnumValuesBase
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas dasar untuk kelas yang mewakili informasi meta dari tipe enumerasi.
type: docs
weight: 807
url: /id/system/enumvaluesbase/
---
## EnumValuesBase kelas

Kelas dasar untuk kelas yang mewakili informasi meta dari tipe enumerasi.

```cpp
class EnumValuesBase
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Mengambil sebuah array dari nama-nama konstanta dalam enumerasi yang ditentukan. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Mengembalikan tipe dasar dari enumerasi yang ditentukan. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Mengembalikan sebuah array yang berisi semua nilai dari tipe enumerasi yang ditentukan. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Mengembalikan sebuah objek yang mewakili nilai konstanta enumerasi dari tipe enumerasi yang ditentukan dengan nama yang diberikan. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Mengonversi nilai bilangan bulat tak bertanda 64-bit yang diberikan menjadi anggota enumerasi. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Mengonversi objek yang diberikan dengan nilai bilangan bulat menjadi anggota enumerasi. |
## Lihat Juga

* ruang nama [System](../)
* perpustakaan [Aspose.Slides](../../)