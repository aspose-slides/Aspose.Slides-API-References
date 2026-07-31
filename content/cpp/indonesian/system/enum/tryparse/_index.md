---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencoba mengonversi string yang diberikan menjadi konstanta enum yang setara.
type: docs
weight: 79
url: /id/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) metode

Mencoba mengonversi string yang diberikan menjadi konstanta enum yang setara.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) yang ditafsirkan sebagai berisi nama konstanta enum |
| result | E\& | Parameter output yang jika konversi berhasil berisi hasil konversi pada fungsi |

### Nilai Kembalian

True jika konversi berhasil, jika tidak - false

## Enum::TryParse(const String\&, bool, E\&) metode

Mencoba mengonversi string yang diberikan menjadi konstanta enum yang setara.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) yang ditafsirkan sebagai berisi nama konstanta enum |
| ignoreCase | **bool** | Menentukan apakah huruf besar/kecil harus diabaikan saat menafsirkan string |
| result | E\& | Parameter output yang jika konversi berhasil berisi hasil konversi pada return fungsi |

### Nilai Kembalian

True jika konversi berhasil, jika tidak - false

## Lihat Juga

* Kelas [String](../../string/)
* Struktur [Enum](../)
* Namespace [System](../../)
* Pustaka [Aspose.Slides](../../../)