---
title: EnumerateFiles()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencari file yang memenuhi kriteria pencarian yang ditentukan baik di direktori yang ditentukan atau di seluruh pohon direktori yang berakar di direktori tersebut.
type: docs
weight: 40
url: /id/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) metode

Mencari file yang memenuhi kriteria pencarian yang ditentukan, baik di direktori yang ditentukan maupun di seluruh pohon direktori yang berakar di direktori tersebut.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur penuh atau relatif ke direktori tempat pencarian |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya pada direktori yang ditentukan atau pada seluruh pohon direktori yang berakar di direktori tersebut |

### Nilai Kembalian

Koleksi dapat diiterasi yang berisi jalur penuh file yang ditemukan yang namanya cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Kelas [String](../../../system/string/)
* Kelas [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)