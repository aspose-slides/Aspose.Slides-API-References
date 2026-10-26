---
title: GetCompareInfo()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan CompareInfo yang terkait dengan budaya yang ditentukan dan menggunakan metode perbandingan string dalam assembly yang ditentukan.
type: docs
weight: 183
url: /id/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) metode

Mendapatkan [CompareInfo](../) yang terkait dengan budaya yang ditentukan dan menggunakan metode perbandingan string dalam assembly yang ditentukan.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| culture | int | Pengidentifikasi budaya (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | assembly yang berisi metode perbandingan string. |

### Nilai Kembali

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) metode

Mendapatkan [CompareInfo](../) yang terkait dengan budaya yang ditentukan dan menggunakan metode perbandingan string dalam assembly yang ditentukan.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama budaya. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | assembly yang berisi metode perbandingan string. |

### Nilai Kembali

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(int) metode

Mendapatkan [CompareInfo](../) yang terkait dengan budaya yang ditentukan.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| culture | int | Pengidentifikasi budaya (LCID). |

### Nilai Kembali

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&) metode

Mendapatkan [CompareInfo](../) yang terkait dengan budaya yang ditentukan.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama budaya. |

### Nilai Kembali

[CompareInfo](../) object.

## Lihat Juga

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Assembly](../../../system.reflection/assembly/)
* Kelas [CompareInfo](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Globalization](../../)
* Library [Aspose.Slides](../../../)