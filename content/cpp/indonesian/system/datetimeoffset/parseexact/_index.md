---
title: ParseExact()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan menjadi objek DateTimeOffset menggunakan format, penyedia format, dan gaya pemformatan yang ditentukan.
type: docs
weight: 716
url: /id/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metode

Mengonversi string yang ditentukan menjadi objek [DateTimeOffset](../) menggunakan format, penyedia format, dan gaya pemformatan yang ditentukan.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) untuk dikonversi. |
| format | const [String](../../string/)\& | String format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Gaya pemformatan tanggal dan waktu. |

### Nilai Kembali

[DateTimeOffset](../) yang setara dengan **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metode

Mengonversi string yang ditentukan menjadi objek [DateTimeOffset](../) menggunakan format, penyedia format, dan gaya pemformatan yang ditentukan.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) untuk dikonversi. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) string format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Gaya pemformatan tanggal dan waktu. |

### Nilai Kembali

[DateTimeOffset](../) yang setara dengan **input**.

## Lihat Juga

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [DateTimeOffset](../)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)