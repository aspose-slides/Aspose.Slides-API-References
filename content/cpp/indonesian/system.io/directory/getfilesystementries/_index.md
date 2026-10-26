---
title: GetFileSystemEntries()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan, baik di direktori yang ditentukan maupun di seluruh pohon direktori yang berakar di direktori tersebut.
type: docs
weight: 92
url: /id/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) metode

Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan, baik di direktori yang ditentukan maupun di seluruh pohon direktori yang berakar di direktori tersebut.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur penuh atau relatif ke direktori tempat pencarian |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file dan direktori yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya di direktori yang ditentukan atau di seluruh pohon direktori yang berakar di direktori tersebut |

### Nilai Kembalian

Array dari jalur penuh file dan direktori yang ditemukan yang namanya cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [Directory](../)
* Ruang Nama [System::IO](../../)
* Library [Aspose.Slides](../../../)