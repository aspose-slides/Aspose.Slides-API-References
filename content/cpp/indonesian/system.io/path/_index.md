---
title: Path
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan metode untuk memanipulasi jalur. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah boleh membuat instance darinya dengan cara apapun.
type: docs
weight: 339
url: /id/system.io/path/
---
## Path kelas

Menyediakan metode untuk memanipulasi jalur. Ini adalah tipe statis tanpa layanan instansi. Anda tidak pernah boleh membuat instansi darinya dengan cara apapun.

```cpp
class Path
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Mengubah ekstensi dalam jalur file yang ditentukan. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Menentukan apakah jalur yang ditentukan valid dengan memeriksa apakah mengandung karakter tidak valid. Pengecualian dilemparkan jika jalur mengandung karakter tidak valid. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Menggabungkan segmen jalur yang ditentukan menjadi satu jalur dengan menyisipkan karakter pemisah direktori di antara segmen jika diperlukan. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menggabungkan dua segmen jalur yang ditentukan menjadi satu jalur dengan menyisipkan karakter pemisah direktori di antara segmen jika diperlukan. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menggabungkan tiga segmen jalur yang ditentukan menjadi satu jalur dengan menyisipkan karakter pemisah direktori di antara segmen jika diperlukan. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menggabungkan empat segmen jalur yang ditentukan menjadi satu jalur dengan menyisipkan karakter pemisah direktori di antara segmen jika diperlukan. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Mengembalikan nama direktori yang dirujuk oleh jalur yang ditentukan. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Mengembalikan ekstensi file yang dirujuk oleh jalur yang ditentukan. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Mengembalikan nama file yang dirujuk oleh jalur yang ditentukan. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Mengembalikan nama tanpa ekstensi dari file yang dirujuk oleh jalur yang ditentukan. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Mengonversi jalur yang ditentukan menjadi jalur absolut. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Mengembalikan array yang berisi karakter yang tidak diizinkan dalam nama file. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Mengembalikan array yang berisi karakter yang tidak diizinkan dalam nama jalur. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Mengembalikan direktori akar dari jalur yang ditentukan. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Mengembalikan nama file yang dihasilkan secara acak. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Membuat file baru dengan nama unik dan mengembalikan jalur lengkap kepadanya. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Membuat file baru dengan nama unik dan mengembalikan jalur lengkap kepadanya. Merupakan sinonim dari metode [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Mengembalikan jalur direktori sementara pengguna saat ini. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Menentukan apakah jalur yang ditentukan merujuk ke file dengan ekstensi. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Menentukan apakah jalur yang ditentukan mengandung akar. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Menormalkan jalur yang ditentukan. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Mengembalikan instance dari kelas boost::filesystem::path yang mewakili jalur yang ditentukan. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Mengembalikan representasi string dari objek path Boost yang ditentukan. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Karakter alternatif yang digunakan untuk memisahkan level direktori dalam sebuah jalur. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Karakter yang digunakan untuk memisahkan level direktori dalam sebuah jalur. |
| static [PathSeparator](./pathseparator/) | Karakter pemisah yang digunakan untuk memisahkan string jalur dalam variabel lingkungan. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Karakter pemisah volume. |

## Catatan

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Membuat nama file acak.
  auto filename = Path::GetRandomFileName();

  // Cetak informasi tentang nama file.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Nama File: qhuzkyqv.y6p
Nama File tanpa ekstensi: qhuzkyqv
Ekstensi: .y6p
*/
```

## Lihat Juga

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)