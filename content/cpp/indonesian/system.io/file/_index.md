---
title: File
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan metode untuk memanipulasi file. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah boleh membuat instance darinya dengan cara apapun.
type: docs
weight: 261
url: /id/system.io/file/
---
## Kelas File

Menyediakan metode untuk memanipulasi file. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah harus membuat instance darinya dengan cara apapun.

```cpp
class File
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Menambahkan string dari koleksi string yang ditentukan ke file yang ditentukan menggunakan pengkodean yang ditentukan dengan menulis setiap string pada baris baru. Jika file yang ditentukan tidak ada, file tersebut akan dibuat. File ditutup setelah menulis semua string. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Menambahkan string yang ditentukan ke file yang ditentukan menggunakan pengkodean yang ditentukan. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Membuat objek [StreamWriter](../streamwriter/) yang menambahkan teks ke file yang ditentukan menggunakan pengkodean UTF-8. Jika file yang ditentukan tidak ada, file tersebut akan dibuat. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Menyalin file yang ditentukan ke lokasi yang ditentukan. Jika file tujuan sudah ada, sebuah parameter menentukan apakah harus ditimpa. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Membuat file baru (atau menimpa yang ada) dan membukanya untuk akses baca dan tulis menggunakan ukuran buffer dan opsi yang ditentukan. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Membuat file baru atau membuka file yang ada untuk menulis teks berencoding UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | BELUM DIIMPLEMENTASIKAN. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Menghapus file atau direktori yang ditentukan. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | BELUM DIIMPLEMENTASIKAN. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Menentukan apakah jalur yang ditentukan merujuk pada file yang ada. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Mengembalikan atribut dari entitas yang ditentukan. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Mengembalikan waktu pembuatan entitas yang ditentukan sebagai waktu lokal. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Mengembalikan waktu pembuatan entitas yang ditentukan sebagai waktu UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Mengembalikan waktu akses terakhir entitas yang ditentukan sebagai waktu lokal. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Mengembalikan waktu akses terakhir entitas yang ditentukan sebagai waktu UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Mengembalikan waktu penulisan terakhir entitas yang ditentukan sebagai waktu lokal. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Mengembalikan waktu penulisan terakhir entitas yang ditentukan sebagai waktu UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Memindahkan file yang ditentukan ke lokasi baru. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Membuka file yang ditentukan dalam mode yang ditentukan untuk membaca dan menulis tanpa berbagi. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Membuka file yang ditentukan dalam mode yang ditentukan, dengan jenis akses dan opsi berbagi yang ditentukan. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Membuka file yang ditentukan hanya untuk membaca, dalam mode 'Open' dengan akses berbagi untuk membaca. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Membuka file yang ada yang ditentukan untuk membaca teks menggunakan pengkodean UTF-8 tanpa berbagi. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Membuka file yang ditentukan hanya untuk menulis, dalam mode 'OpenOrCreate' tanpa berbagi. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Membaca konten file biner yang ditentukan ke array byte. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Membaca konten file teks yang ditentukan baris demi baris ke array string menggunakan pengkodean karakter yang ditentukan. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Membaca konten file teks yang ditentukan ke satu objek [String](../../system/string/) menggunakan pengkodean karakter yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Membaca konten file teks yang ditentukan baris demi baris menggunakan pengkodean karakter yang ditentukan dan mengembalikan koleksi dapat diiterasi berupa string, masing-masing mewakili satu baris konten file. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Mengganti isi satu file dengan file lain dan membuat cadangan file yang diganti. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Mengatur atribut yang ditentukan pada file yang ditentukan. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | BELUM DIIMPLEMENTASIKAN. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | BELUM DIIMPLEMENTASIKAN. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | BELUM DIIMPLEMENTASIKAN. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | BELUM DIIMPLEMENTASIKAN. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Mengatur waktu penulisan terakhir entitas yang ditentukan sebagai waktu lokal. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Mengatur waktu penulisan terakhir entitas yang ditentukan sebagai waktu UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Menimpa file biner yang ditentukan dan menulis byte yang ditentukan ke dalamnya. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Membuat file teks baru atau menimpa yang ada dan menulis semua string dari koleksi dapat diiterasi berisi string yang ditentukan ke dalamnya, setiap string pada baris baru, menggunakan pengkodean yang ditentukan. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Membuat file teks baru atau menimpa yang ada dan menulis semua string dari array string yang ditentukan ke dalamnya, setiap string pada baris baru, menggunakan pengkodean yang ditentukan. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Membuat file teks baru atau menimpa yang ada dan menulis konten string yang ditentukan ke dalamnya menggunakan pengkodean yang ditentukan. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Nilai default jumlah byte yang di-buffer selama membaca dari dan menulis ke file. |

## Lihat Juga

* Namespace [System::IO](../)
* Pustaka [Aspose.Slides](../../)