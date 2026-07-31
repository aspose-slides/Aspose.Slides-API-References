---
title: TryParseExact()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencoba mengubah string yang ditentukan menjadi objek DateTimeOffset menggunakan format yang ditentukan, penyedia format, dan gaya pemformatan.
type: docs
weight: 742
url: /id/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Mencoba mengubah string yang ditentukan menjadi objek [DateTimeOffset](../) menggunakan format yang ditentukan, penyedia format, dan gaya pemformatan.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) untuk dikonversi. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Array string format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Gaya pemformatan tanggal dan waktu. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) yang setara dengan **input**. |

### Nilai Kembali

true jika **input** berhasil dikonversi, jika tidak - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Mencoba mengubah string yang ditentukan menjadi objek [DateTimeOffset](../) menggunakan format yang ditentukan, penyedia format, dan gaya pemformatan.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) untuk dikonversi. |
| format | const [String](../../string/)\& | String format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Gaya pemformatan tanggal dan waktu. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) yang setara dengan **input**. |

### Nilai Kembali

true jika **input** berhasil dikonversi, jika tidak - false.

## Lihat Juga

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)