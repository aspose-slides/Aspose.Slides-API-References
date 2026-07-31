---
title: DirectoryInfo
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili jalur sistem file, sebuah direktori yang dirujuk oleh jalur ini, dan menyediakan metode instansi untuk memanipulasi direktori. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instansi tipe ini di stack atau menggunakan operator new, karena dapat menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 248
url: /id/system.io/directoryinfo/
---
## DirectoryInfo kelas


Mewakili jalur sistem file, sebuah direktori yang dirujuk oleh jalur ini dan menyediakan metode instansi untuk memanipulasi direktori. Objek kelas ini harus hanya dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instansi tipe ini di stack atau menggunakan operator new, karena akan menghasilkan error runtime dan/atau fault asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Create](./create/)() | Membuat sebuah direktori pada jalur yang direpresentasikan oleh objek saat ini. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Membuat subdirektori pada jalur yang ditentukan. |
| void [Delete](./delete/)() override | Menghapus direktori yang dirujuk oleh jalur yang direpresentasikan oleh objek saat ini jika direktori tersebut kosong. |
| void [Delete](./delete/)(**bool**) | Menghapus direktori yang dirujuk oleh jalur yang direpresentasikan oleh objek saat ini. Parameter menentukan apakah isi direktori harus dihapus secara rekursif jika direktori tidak kosong. |
| [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Membuat sebuah instansi dari kelas [DirectoryInfo](./) pada jalur yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Mengembalikan koleksi enumerable yang berisi semua direktori yang terletak dalam direktori yang direpresentasikan oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Mencari direktori yang memenuhi kriteria pencarian yang ditentukan dalam direktori yang direpresentasikan oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari direktori yang memenuhi kriteria pencarian yang ditentukan baik dalam direktori yang direpresentasikan oleh objek saat ini atau dalam seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Mengembalikan koleksi enumerable yang berisi semua file yang terletak dalam direktori yang direpresentasikan oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Mencari file yang memenuhi kriteria pencarian yang ditentukan dalam direktori yang direpresentasikan oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari file yang memenuhi kriteria pencarian yang ditentukan baik dalam direktori yang direpresentasikan oleh objek saat ini atau dalam seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Mengembalikan koleksi enumerable yang berisi semua file dan direktori yang terletak dalam direktori yang direpresentasikan oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan dalam direktori yang direpresentasikan oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan baik dalam direktori yang direpresentasikan oleh objek saat ini atau dalam seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Tidak melakukan apa-apa. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Mengembalikan atribut entitas yang direpresentasikan oleh objek saat ini. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Mengembalikan waktu pembuatan entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Mengembalikan waktu pembuatan entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| **bool** [get_Exists](./get_exists/)() override | Menentukan apakah jalur yang direpresentasikan oleh objek saat ini merujuk pada direktori yang ada. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Mengembalikan ekstensi file yang direpresentasikan oleh objek saat ini. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Mengembalikan nama lengkap (termasuk jalur) dari entitas yang direpresentasikan oleh objek saat ini. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Mengembalikan waktu akses terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Mengembalikan waktu akses terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Mengembalikan waktu penulisan terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Mengembalikan waktu penulisan terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Mengembalikan nama entitas yang dirujuk oleh jalur yang direpresentasikan oleh objek saat ini. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Mengembalikan pointer berbagi ke objek [DirectoryInfo](./) yang mewakili jalur yang merujuk ke direktori induk dari direktori yang direpresentasikan oleh objek saat ini. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Mengembalikan pointer berbagi ke objek [DirectoryInfo](./) yang mewakili jalur yang merujuk ke direktori akar dari direktori yang direpresentasikan oleh objek saat ini. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Mengembalikan array yang berisi pointer berbagi ke objek [DirectoryInfo](./) yang mewakili semua direktori yang terletak dalam direktori yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Mencari direktori yang memenuhi kriteria pencarian yang ditentukan dalam direktori yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari direktori yang memenuhi kriteria pencarian yang ditentukan baik dalam direktori yang direpresentasikan oleh objek saat ini atau dalam seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Mengembalikan array yang berisi pointer berbagi ke objek [FileInfo](../fileinfo/) yang mewakili semua direktori yang terletak dalam direktori yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Mencari file yang memenuhi kriteria pencarian yang ditentukan dalam direktori yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari file yang memenuhi kriteria pencarian yang ditentukan baik dalam direktori yang direpresentasikan oleh objek saat ini atau dalam seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Mengembalikan array yang berisi pointer berbagi ke objek [FileSystemInfo](../filesysteminfo/) yang mewakili semua file dan direktori yang terletak dalam direktori yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan dalam direktori yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan baik dalam direktori yang direpresentasikan oleh objek saat ini atau dalam seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instansi dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan C# lock() yang mengunci. Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Memindahkan direktori yang direpresentasikan oleh objek saat ini beserta seluruh isinya ke lokasi yang ditentukan. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa-apa, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa-apa, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| void [Refresh](../filesysteminfo/refresh/)() | Menyegarkan keadaan objek saat ini. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi berbagi sebesar nilai yang ditentukan. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Menetapkan atribut yang ditentukan pada entitas yang direpresentasikan oleh objek saat ini. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Menetapkan waktu pembuatan entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Menetapkan waktu pembuatan entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Menetapkan waktu akses terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Menetapkan waktu akses terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Menetapkan waktu penulisan terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu lokal. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Menetapkan waktu penulisan terakhir entitas yang direpresentasikan oleh objek saat ini sebagai waktu UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan pengalihan pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai terkini penghitung referensi berbagi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi berbagi. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi berbagi. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Mengembalikan string yang berisi jalur yang direpresentasikan oleh objek saat ini. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() yang membebaskan kunci. Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)