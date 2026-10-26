---
title: GetCultureInfo()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan kultur berdasarkan namanya. Sama dengan CreateSpecificCulture.
type: docs
weight: 586
url: /id/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) metode


Mendapatkan kultur berdasarkan namanya. Sama dengan CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama kultur yang telah ditentukan atau nama objek kultur yang ada. |

### Nilai Kembalian

Objek kultur yang baru dibuat.

## CultureInfo::GetCultureInfo(const String\&, const String\&) metode


Mendapatkan kultur berdasarkan namanya.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama kultur. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Nama kultur yang digunakan untuk objek [TextInfo](../../textinfo/) dan [CompareInfo](../../compareinfo/). |

### Nilai Kembalian

Objek kultur.

## CultureInfo::GetCultureInfo(int32_t) metode


Mendapatkan kultur berdasarkan id.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| culture | **int32_t** | Pengidentifikasi kultur. |

### Nilai Kembalian

Objek kultur yang baru dibuat.

## Lihat Juga

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Kelas [String](../../../system/string/)
* Kelas [CultureInfo](../)
* Ruang Nama [System::Globalization](../../)
* Library [Aspose.Slides](../../../)