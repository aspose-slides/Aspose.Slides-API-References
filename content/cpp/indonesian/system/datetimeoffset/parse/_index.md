---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan menjadi ekivalen DateTimeOffset.
type: docs
weight: 703
url: /id/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) metode

Mengonversi string yang ditentukan menjadi ekivalen [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) untuk dikonversi. |

### Nilai Kembali

[DateTimeOffset](../) yang setara dengan **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metode

Mengonversi string yang ditentukan menjadi objek [DateTimeOffset](../) menggunakan penyedia format dan gaya pemformatan yang ditentukan.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) untuk dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Gaya pemformatan tanggal dan waktu. |

### Nilai Kembali

[DateTimeOffset](../) yang setara dengan **input**.

## Lihat Juga

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)