---
title: CheckPath()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah jalur yang ditentukan valid dengan memeriksa apakah mengandung karakter tidak valid. Sebuah pengecualian dilemparkan jika jalur mengandung karakter tidak valid.
type: docs
weight: 209
url: /id/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) metode

Menentukan apakah jalur yang ditentukan valid dengan memeriksa apakah ia mengandung karakter tidak valid. Sebuah pengecualian dilemparkan jika jalur mengandung karakter tidak valid.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur yang akan diperiksa |
| msg | const [String](../../../system/string/)\& | Pesan yang akan diberikan ke konstruktor objek pengecualian |
| allow_empty | **bool** | Menentukan apakah string kosong atau null harus dianggap sebagai jalur yang benar (true) atau tidak (false); jika parameter ini false dan **path** kosong, ArgumentException dilemparkan; jika parameter ini false dan **path** null, ArgumentNullException dilemparkan |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [Path](../)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)