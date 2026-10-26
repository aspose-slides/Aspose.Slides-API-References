---
title: UnmanagedMemoryStream
second_title: Referensi API Aspose.Slides untuk C++
description: "Menyediakan akses ke memori yang tidak dikelola. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan error runtime dan/atau kesalahan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 456
url: /id/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream kelas

Menyediakan akses ke memori yang tidak dikelola. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan error runtime dan/atau kesalahan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Memulai operasi baca asinkron. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Memulai operasi tulis asinkron. |
| virtual void [Close](../stream/close/)() | Menutup aliran. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Menyalin byte ke aliran yang ditentukan. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Menyalin byte ke aliran yang ditentukan, menggunakan ukuran buffer yang ditentukan. |
| void [Dispose](../stream/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup aliran. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Menunggu sampai operasi baca asinkron yang ditentukan selesai. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Mengakhiri operasi tulis asinkron. Menunggu sampai operasi tulis asinkron yang ditentukan selesai. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk tujuan internal. |
| void [Flush](./flush/)() override | Tidak melakukan apa pun. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asinkron membersihkan semua buffer untuk aliran ini, menyebabkan data yang dibuffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Secara asinkron membersihkan semua buffer untuk aliran ini, menyebabkan data yang dibuffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan. |
| **bool** [get_CanRead](./get_canread/)() const override | Menentukan apakah aliran dapat dibaca. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Menentukan apakah aliran mendukung pencarian. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Mendapatkan nilai yang menentukan apakah aliran saat ini dapat berakhir (timeout). |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Menentukan apakah aliran dapat ditulis. |
| virtual **int64_t** [get_Capacity](./get_capacity/)() const | Mengembalikan kapasitas saat ini dari buffer memori yang mendasari. |
| **int64_t** [get_Length](./get_length/)() const override | Mengembalikan panjang aliran dalam byte. |
| **int64_t** [get_Position](./get_position/)() const override | Mengembalikan posisi saat ini dari aliran. |
| **uint8_t** * [get_PositionPointer](./get_positionpointer/)() | TIDAK DIIMPLEMENTASIKAN. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Mendapatkan nilai, dalam milidetik, yang menentukan berapa lama aliran akan mencoba membaca sebelum berakhir (timeout). |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Mendapatkan nilai, dalam milidetik, yang menentukan berapa lama aliran akan mencoba menulis sebelum berakhir (timeout). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan cloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruk copy pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruk copy pada subclass. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke span byte yang ditentukan. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asinkron membaca urutan byte dari aliran saat ini, memajukan posisi dalam aliran sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Secara asinkron membaca urutan byte dari aliran saat ini, memajukan posisi dalam aliran sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan. |
| virtual int [ReadByte](../stream/readbyte/)() | Membaca satu byte dari aliran dan mengembalikan nilai integer 32-bit yang setara dengan nilai byte yang dibaca. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Mengatur posisi aliran yang direpresentasikan oleh objek saat ini. |
| void [set_Position](./set_position/)(**int64_t**) override | Mengatur posisi aliran. |
| void [set_PositionPointer](./set_positionpointer/)(**uint8_t** *) | TIDAK DIIMPLEMENTASIKAN. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Mengatur nilai yang menentukan apakah aliran saat ini dapat berakhir (timeout). |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Mengatur nilai, dalam milidetik, yang menentukan berapa lama aliran akan mencoba membaca sebelum berakhir (timeout). |
| void [SetLength](./setlength/)(**int64_t**) override | TIDAK DIIMPLEMENTASIKAN. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan pengalihan pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci (unlock) pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**) | Membuat instance baru dari [UnmanagedMemoryStream](./). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**, **int64_t**, [FileAccess](../fileaccess/)) | Membuat instance baru dari [UnmanagedMemoryStream](./). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | TIDAK DIIMPLEMENTASIKAN. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | TIDAK DIIMPLEMENTASIKAN. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Menulis subrentang byte yang ditentukan dari span byte yang ditentukan ke aliran. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asinkron menulis urutan byte ke aliran saat ini, memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Secara asinkron menulis urutan byte ke aliran saat ini, memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Menulis nilai integer tak bertanda 8-bit yang ditentukan ke aliran. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Null](../stream/null/) | Sebuah aliran tanpa penyimpanan dasar. |

## Lihat Juga

* Kelas [Stream](../stream/)
* Ruang Nama [System::IO](../)
* Perpustakaan [Aspose.Slides](../../)