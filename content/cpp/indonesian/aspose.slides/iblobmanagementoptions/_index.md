---
title: IBlobManagementOptions
second_title: Referensi API Aspose.Slides untuk C++
description: Binary Large Object (BLOB) adalah data biner yang disimpan sebagai satu entitas - yaitu BLOB dapat berupa audio, video, atau presentasi itu sendiri. Berbagai teknik digunakan untuk mengoptimalkan konsumsi memori saat bekerja dengan BLOB - yang sudah disimpan dalam presentasi atau dapat ditambahkan kemudian secara programatis. Dengan menggunakan IBlobManagementOptions Anda dapat mengubah berbagai aspek perilaku terkait penanganan BLOB selama masa hidup instance IPresentation.
type: docs
weight: 1535
url: /id/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions kelas


BLOB (Binary Large Object) adalah data biner yang disimpan sebagai satu entitas - misalnya BLOB dapat berupa audio, video, atau presentasi itu sendiri. Berbagai teknik digunakan untuk mengoptimalkan konsumsi memori saat bekerja dengan BLOBs - yang sudah disimpan dalam presentasi atau dapat ditambahkan kemudian secara programatis. Menggunakan [IBlobManagementOptions](./) Anda dapat mengubah berbagai aspek perilaku terkait penanganan BLOBs untuk masa hidup instance [IPresentation](../ipresentation/).

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## Metode

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Menyimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Menyimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOBs, yang sangat mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB dalam memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) akan digunakan. Menyimpan BLOB dalam memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau kebutuhan Anda. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | Properti ini menentukan apakah sebuah instance dari [Presentation](../presentation/) kelas dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. Jika instance menjadi pemilik, ia mengunci sumber. Ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOBs, tetapi sumber (stream atau file) tidak dapat diubah selama masa hidup [Presentation](../presentation/). Ini adalah contoh: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | Path akar tempat file sementara akan dibuat. Direktori sementara [System](../../system/) akan digunakan secara default. Proses host harus memiliki izin untuk membuat file dan folder di sana. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOBs, yang sangat mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB dalam memori. Secara default, semua BLOB dimuat ke memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) akan digunakan. Menyimpan BLOB dalam memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau kebutuhan Anda. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | Properti ini menentukan apakah sebuah instance dari [Presentation](../presentation/) kelas dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. Jika instance menjadi pemilik, ia mengunci sumber. Ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOBs, tetapi sumber (stream atau file) tidak dapat diubah selama masa hidup [Presentation](../presentation/). Ini adalah contoh: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | Path akar tempat file sementara akan dibuat. Direktori sementara [System](../../system/) akan digunakan secara default. Proses host harus memiliki izin untuk membuat file dan folder di sana. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)