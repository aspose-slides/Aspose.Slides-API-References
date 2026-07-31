---
title: Debug
second_title: Referensi API Aspose.Slides untuk C++
description: Koleksi metode debug yang memungkinkan mengirimkan informasi debug ke pendengar yang terdaftar. Semua fungsi output hanya bekerja di Debug saja. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah boleh membuat instance darinya dengan cara apapun.
type: docs
weight: 105
url: /id/system.diagnostics/debug/
---
## Struct Debug

Koleksi metode debug yang memungkinkan mengirimkan informasi debug ke pendengar yang terdaftar. Semua fungsi output hanya bekerja di [Debug](./). Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah boleh membuat instance darinya dengan cara apapun.

```cpp
class Debug
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Menegaskan kondisi dan mengirimkan informasi saat gagal. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Menegaskan kondisi dan mengirimkan informasi saat gagal. |
| static void [Assert](./assert/)(**bool**, const char *) | Menegaskan kondisi dan mengirimkan informasi saat gagal. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menegaskan kondisi dan mengirimkan informasi saat gagal. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Mengirim pesan kegagalan. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Mengakses daftar statis pendengar. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Mencetak pesan ke antarmuka debug. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Mencetak pesan ke antarmuka debug. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Menulis string ke antarmuka debug. |
| static void [Write](./write/)(const char_t *) | Menulis string ke antarmuka debug. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Menulis string ke antarmuka debug jika kondisi benar. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Menulis baris ke antarmuka debug. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menulis baris ke antarmuka debug. |
| static void [WriteLine](./writeline/)(const char_t *) | Menulis baris ke antarmuka debug. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Menulis baris ke antarmuka debug. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Menulis baris ke antarmuka debug jika kondisi benar. |

## Lihat Juga

* Namespace [System::Diagnostics](../)
* Perpustakaan [Aspose.Slides](../../)