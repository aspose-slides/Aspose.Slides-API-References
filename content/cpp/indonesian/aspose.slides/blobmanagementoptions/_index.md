---
title: BlobManagementOptions
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili opsi yang dapat digunakan untuk mengelola aturan penanganan BLOB dan pengaturan BLOB lainnya.
type: docs
weight: 196
url: /id/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions kelas

Mewakili opsi yang dapat digunakan untuk mengelola aturan penanganan BLOB dan pengaturan BLOB lainnya.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Metode

| Method | Description |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Membuat opsi manajemen blob default baru. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Menirukan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Menirukan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi penggunaan memori tetapi memerlukan izin untuk membuat file. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya ketika batas ini tercapai mekanisme alternatif (seperti file sementara) digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau kebutuhan Anda. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Properti ini menentukan apakah sebuah instance dari kelas [Presentation](../presentation/) dapat menjadi pemilik sumber - file atau aliran selama masa hidup instance. Jika instance adalah pemilik, ia mengunci sumber. Hal ini membantu meningkatkan penggunaan memori dan kinerja saat bekerja dengan BLOB, tetapi sumber (aliran atau file) tidak dapat diubah selama masa hidup instance [Presentation](../presentation/). |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | Path root di mana file sementara akan dibuat. Direktori sementara [System](../../system/) akan digunakan secara default. Proses hosting harus memiliki izin untuk membuat file dan folder di sana. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan pengkloningan tipe kustom. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi penggunaan memori tetapi memerlukan izin untuk membuat file. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Mendefinisikan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya ketika batas ini tercapai mekanisme alternatif (seperti file sementara) digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau kebutuhan Anda. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Properti ini menentukan apakah sebuah instance dari kelas [Presentation](../presentation/) dapat menjadi pemilik sumber - file atau aliran selama masa hidup instance. Jika instance adalah pemilik, ia mengunci sumber. Hal ini membantu meningkatkan penggunaan memori dan kinerja saat bekerja dengan BLOB, tetapi sumber (aliran atau file) tidak dapat diubah selama masa hidup instance [Presentation](../presentation/). |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | Path root di mana file sementara akan dibuat. Direktori sementara [System](../../system/) akan digunakan secara default. Proses hosting harus memiliki izin untuk membuat file dan folder di sana. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Tetapkan argumen templat ke-n menjadi pointer lemah (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembuka pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* kelas [IBlobManagementOptions](../iblobmanagementoptions/)
* Ruang nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)