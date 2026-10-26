---
title: EnumerateDirectories()
second_title: Aspose.Slides untuk Referensi API C++
description: Mencari direktori yang memenuhi kriteria pencarian yang ditentukan baik di direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori yang ditentukan.
type: docs
weight: 27
url: /id/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) metode

Mencari direktori yang memenuhi kriteria pencarian yang ditentukan baik di direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori yang ditentukan.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur lengkap atau relatif ke direktori yang akan dicari |
| searchPattern | const [String](../../../system/string/)\& | Pola nama direktori yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya di direktori yang ditentukan atau di seluruh pohon direktori yang berakar pada direktori yang ditentukan |

### Nilai Kembali

Koleksi enumerable dari jalur lengkap direktori yang ditemukan yang namanya cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)