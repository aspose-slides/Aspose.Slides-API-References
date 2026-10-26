---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencoba mengonversi string yang ditentukan menjadi objek DateTimeOffset.
type: docs
weight: 729
url: /id/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) metode

Mencoba mengonversi string yang ditentukan menjadi objek [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) untuk dikonversi. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) yang setara dengan **input**. |

### Nilai Kembali

true jika **input** berhasil dikonversi, jika tidak - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metode

Mencoba mengonversi string yang ditentukan menjadi objek [DateTimeOffset](../) menggunakan format provider dan gaya pemformatan yang ditentukan.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) untuk dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Gaya pemformatan tanggal dan waktu. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) yang setara dengan **input**. |

### Nilai Kembali

true jika **input** berhasil dikonversi, jika tidak - false.

## Lihat Juga

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [DateTimeOffset](../)
* Kelas [IFormatProvider](../../iformatprovider/)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)