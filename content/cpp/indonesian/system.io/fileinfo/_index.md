---
title: FileInfo
second_title: Aspose.Slides untuk Referensi API C++
description: "Mewakili jalur ke sebuah file dan file yang dirujuk oleh jalur ini serta menyediakan metode untuk memanipulasinya. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 274
url: /id/system.io/fileinfo/
---
## FileInfo kelas

Mewakili jalur ke sebuah file dan file yang dirujuk oleh jalur ini serta menyediakan metode untuk memanipulasinya. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Membuka file yang direpresentasikan oleh objek saat ini untuk menulis teks menggunakan enkoding UTF-8, dalam mode 'Append' tanpa berbagi. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Menyalin file yang direpresentasikan oleh objek saat ini ke lokasi yang ditentukan. Jika file tujuan sudah ada, penyalinan gagal. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Menyalin file yang direpresentasikan oleh objek saat ini ke lokasi yang ditentukan. Sebuah parameter menentukan apakah file tujuan yang sudah ada harus ditimpa. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Membuat file di lokasi yang ditentukan oleh jalur yang direpresentasikan oleh objek saat ini dan membukanya untuk membaca dan menulis, dalam mode truncate dan tanpa berbagi. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Membuat file di lokasi yang ditentukan oleh jalur yang direpresentasikan oleh objek saat ini dan membukanya untuk menulis teks menggunakan enkoding UTF-8 tanpa berbagi. |
| void [Decrypt](./decrypt/)() | TIDAK DIIMPLEMENTASIKAN. |
| void [Delete](./delete/)() override | Menghapus file yang direpresentasikan oleh objek saat ini. |
| void [Encrypt](./encrypt/)() | TIDAK DIIMPLEMENTASIKAN. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Membuat instance baru dari kelas [FileInfo](./) yang merepresentasikan file yang ditentukan. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Tidak melakukan apa pun. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Mengembalikan atribut dari entitas yang direpresentasikan oleh objek saat ini. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Mengembalikan waktu pembuatan entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Mengembalikan waktu pembuatan entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Mengembalikan objek [DirectoryInfo](../directoryinfo/) yang merepresentasikan direktori tempat file yang direpresentasikan oleh objek saat ini berada. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Mengembalikan nama lengkap direktori tempat file yang direpresentasikan oleh objek saat ini berada. |
| **bool** [get_Exists](./get_exists/)() override | Mengembalikan nilai yang menunjukkan apakah file ada. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Mengembalikan ekstensi file yang direpresentasikan oleh objek saat ini. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Mengembalikan nama lengkap (termasuk jalur) dari entitas yang direpresentasikan oleh objek saat ini. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Mengembalikan nilai yang menunjukkan apakah atribut ReadOnly diatur. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Mengembalikan waktu akses terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Mengembalikan waktu akses terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Mengembalikan waktu penulisan terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Mengembalikan waktu penulisan terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| **int64_t** [get_Length](./get_length/)() | Mengembalikan ukuran file dalam byte. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Mengembalikan nama file. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merepresentasikan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Memindahkan file yang direpresentasikan oleh objek saat ini ke lokasi yang ditentukan. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Membuka file yang direpresentasikan oleh objek saat ini dalam mode yang ditentukan untuk membaca dan menulis serta tanpa berbagi. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Membuka file yang direpresentasikan oleh objek saat ini dalam mode yang ditentukan, dengan tipe akses yang ditentukan dan tanpa berbagi. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Membuka file yang direpresentasikan oleh objek saat ini dalam mode yang ditentukan, dengan tipe akses yang ditentukan dan opsi berbagi. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Membuka file yang direpresentasikan oleh objek saat ini hanya untuk membaca, dalam mode 'Open' dengan akses berbagi untuk membaca. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Membuka file yang sudah ada di lokasi yang ditentukan oleh jalur yang direpresentasikan oleh objek saat ini untuk membaca teks menggunakan enkoding UTF-8 tanpa berbagi. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Membuka file yang direpresentasikan oleh objek saat ini hanya untuk menulis, dalam mode 'OpenOrCreate' tanpa berbagi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| void [Refresh](../filesysteminfo/refresh/)() | Menyegarkan keadaan objek saat ini. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Mengganti isi file tujuan yang ditentukan dengan file yang direpresentasikan oleh objek [FileInfo](./) saat ini dan membuat salinan cadangan file yang diganti. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Mengganti isi file tujuan yang ditentukan dengan file yang direpresentasikan oleh objek [FileInfo](./) saat ini dan membuat salinan cadangan file yang diganti. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Menetapkan atribut yang ditentukan pada entitas yang direpresentasikan oleh objek saat ini. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Menetapkan waktu pembuatan entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Menetapkan waktu pembuatan entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Menetapkan atau menghapus atribut ReadOnly pada file. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Menetapkan waktu akses terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Menetapkan waktu akses terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Menetapkan waktu penulisan terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Menetapkan waktu penulisan terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Seharusnya tidak dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Seharusnya tidak dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Mengembalikan jalur yang direpresentasikan oleh objek saat ini. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi weak. Seharusnya tidak dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi weak. Seharusnya tidak dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [FileSystemInfo](../filesysteminfo/)
* Ruang Nama [System::IO](../)
* Pustaka [Aspose.Slides](../../)