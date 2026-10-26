---
title: GetDirectories()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencari direktori yang memenuhi kriteria pencarian yang ditentukan, baik di direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut.
type: docs
weight: 66
url: /id/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) metode

Mencari direktori yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori yang ditentukan.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Path lengkap atau relatif ke direktori tempat pencarian |
| searchPattern | const [String](../../../system/string/)\& | Pola nama direktori yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya pada direktori yang ditentukan atau pada seluruh pohon direktori yang berakar pada direktori yang ditentukan |

### Nilai Kembali

Array jalur lengkap dari direktori yang ditemukan yang namanya cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)