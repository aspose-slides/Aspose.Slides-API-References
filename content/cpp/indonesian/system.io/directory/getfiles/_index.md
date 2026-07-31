---
title: GetFiles()
second_title: Aspose.Slides for C++ Referensi API
description: Mencari file yang memenuhi kriteria pencarian yang ditentukan, baik di direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut.
type: docs
weight: 79
url: /id/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) method

Mencari file yang memenuhi kriteria pencarian yang ditentukan, baik di direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Path lengkap atau relatif ke direktori tempat pencarian |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya pada direktori yang ditentukan atau pada seluruh pohon direktori yang berakar pada direktori tersebut |

### Nilai Kembalian

Array yang berisi jalur lengkap dari file yang ditemukan yang namanya cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [Directory](../)
* Ruang Nama [System::IO](../../)
* Library [Aspose.Slides](../../../)