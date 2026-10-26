---
title: Directory
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi metode untuk memanipulasi direktori. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh pernah membuat instance darinya dengan cara apa pun.
type: docs
weight: 235
url: /id/system.io/directory/
---
## Kelas Directory

Berisi metode untuk memanipulasi direktori. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh pernah membuat instansi darinya dengan cara apa pun.

```cpp
class Directory
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Membuat semua direktori pada jalur yang ditentukan jika belum ada. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Menghapus file atau direktori yang ditentukan. Tidak melempar pengecualian. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari direktori yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari file yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Menentukan apakah jalur yang ditentukan mengacu pada direktori yang ada. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Mengembalikan waktu pembuatan entitas yang ditentukan sebagai waktu lokal. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Mengembalikan waktu pembuatan entitas yang ditentukan sebagai waktu UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Mengembalikan nama lengkap (termasuk jalur) dari direktori saat ini. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari direktori yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Mengembalikan direktori akar dari jalur yang ditentukan. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari file yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang ditentukan maupun di seluruh pohon direktori yang berakar pada direktori tersebut. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Mengembalikan waktu akses terakhir entitas yang ditentukan sebagai waktu lokal. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Mengembalikan waktu akses terakhir entitas yang ditentukan sebagai waktu UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Mengembalikan waktu penulisan terakhir entitas yang ditentukan sebagai waktu lokal. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Mengembalikan waktu penulisan terakhir entitas yang ditentukan sebagai waktu UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | TIDAK DIIMPLEMENTASIKAN. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Mengembalikan shared pointer ke objek [DirectoryInfo](../directoryinfo/) yang mewakili direktori induk dari entitas yang ditentukan. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Memindahkan entitas yang ditentukan ke lokasi baru. Jika entitas yang dipindahkan adalah direktori, maka dipindahkan beserta seluruh isinya. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Mengatur waktu pembuatan entitas yang ditentukan sebagai waktu lokal. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Mengatur waktu pembuatan entitas yang ditentukan sebagai waktu UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Mengatur direktori saat ini. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Mengatur waktu akses terakhir entitas yang ditentukan sebagai waktu lokal. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Mengatur waktu akses terakhir entitas yang ditentukan sebagai waktu UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Mengatur waktu penulisan terakhir entitas yang ditentukan sebagai waktu lokal. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Mengatur waktu penulisan terakhir entitas yang ditentukan sebagai waktu UTC. |

## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Alias untuk shared pointer ke objek IEnumerable yang mengiterasi sekumpulan objek [String](../../system/string/). |

## Catatan



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Buat string yang berisi jalur ke direktori.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Periksa apakah direktori ada.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Cetak informasi direktori sementara.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Direktori 'C:\' ada.
Direktori 'C:\Some directory' tidak ada.
Direktori 'C:\Users\lanor\AppData\Local\Temp\' ada.
Waktu Pembuatan: 27.08.2021 14:21:42
Waktu Akses Terakhir: 07.10.2021 12:16:41
Waktu Penulisan Terakhir: 07.10.2021 12:16:41
*/
```

## Lihat Juga

* Ruang Nama [System::IO](../)
* Pustaka [Aspose.Slides](../../)