---
title: BasicSTDOStreamWrapper
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pembungkus mirip System.IO.Stream untuk std::basic_ostream dan objek turunannya. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kesalahan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk memberikannya ke fungsi sebagai argumen."
type: docs
weight: 27
url: /id/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper kelas

Mewakili pembungkus mirip [System.IO.Stream](../stream/) untuk std::basic_ostream dan objek turunannya. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk memberikannya ke fungsi sebagai argumen.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Membuat instance baru dari [BasicSTDOStreamWrapper](./). |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | Konstruktor penyalin. Dihapus. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Memulai operasi baca asynchronous. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Memulai operasi tulis asynchronous. |
| virtual void [Close](../stream/close/)() | Menutup stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Menyalin byte ke stream yang ditentukan. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Menyalin byte ke stream yang ditentukan, menggunakan ukuran buffer yang ditentukan. |
| void [Dispose](../stream/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Menunggu hingga operasi baca asynchronous yang ditentukan selesai. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Mengakhiri operasi tulis asynchronous. Menunggu hingga operasi tulis asynchronous yang ditentukan selesai. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| void [Flush](./flush/)() override | Membersihkan buffer stream ini dan menulis semua data yang dibuffer ke penyimpanan dasar. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asynchronous membersihkan semua buffer untuk stream ini, menyebabkan semua data yang dibuffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Secara asynchronous membersihkan semua buffer untuk stream ini, menyebabkan semua data yang dibuffer ditulis ke perangkat dasar, dan memantau permintaan pembatalan. |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | Menentukan apakah stream mendukung pembacaan. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Menentukan apakah stream mendukung pencarian. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Mendapatkan nilai yang menentukan apakah stream saat ini dapat timeout. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Mengembalikan panjang stream. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Mengembalikan posisi saat ini dari stream. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Mendapatkan nilai, dalam milidetik, yang menentukan berapa lama stream akan mencoba membaca sebelum timeout. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Mendapatkan nilai, dalam milidetik, yang menentukan berapa lama stream akan mencoba menulis sebelum timeout. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan konstruktor penyalin untuk subclass. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | Operator penugasan penyalin. Dihapus. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Operator penugasan penyalin. Dihapus. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan konstruktor penyalin untuk subclass. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Jika mode pembungkus adalah biner, membaca jumlah byte yang ditentukan dari stream, jika tidak membaca jumlah karakter yang ditentukan dan mengonversinya ke tipe **uint8_t**. Menulis hasil pembacaan ke array byte yang ditentukan. Tidak didukung! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Membaca jumlah byte yang ditentukan dari stream dan menuliskannya ke array byte yang ditentukan. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Membaca jumlah byte yang ditentukan dari stream dan menuliskannya ke array byte yang ditentukan. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Membaca jumlah byte yang ditentukan dari stream dan menuliskannya ke span byte yang ditentukan. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asynchronous membaca urutan byte dari stream saat ini, memajukan posisi dalam stream sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Secara asynchronous membaca urutan byte dari stream saat ini, memajukan posisi dalam stream sebesar jumlah byte yang dibaca, dan memantau permintaan pembatalan. |
| int [ReadByte](./readbyte/)() override | Jika mode pembungkus adalah biner, membaca satu byte dari penyimpanan karakter terdekripsi terakhir, jika tidak membaca satu karakter dari stream dan mengonversinya ke tipe **uint8_t**. Tidak didukung! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi berbagi sebesar nilai yang ditentukan. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | Informasi RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Mengatur posisi stream yang direpresentasikan oleh objek saat ini. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Mengatur posisi stream. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Mengatur nilai yang menentukan apakah stream saat ini dapat timeout. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Mengatur nilai, dalam milidetik, yang menentukan berapa lama stream akan mencoba membaca sebelum timeout. |
| void [SetLength](./setlength/)(**int64_t**) override | Mengatur panjang stream yang direpresentasikan oleh objek saat ini. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi berbagi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi berbagi. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi berbagi. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Konstruktor penyalin. Dihapus. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembebasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Jika mode pembungkus adalah biner, menulis ke stream subrentang byte yang ditentukan dari array byte yang ditentukan, jika tidak mengonversi subrentang byte tersebut ke tipe char_type kemudian menulis hasilnya ke stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke stream. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Menulis subrentang byte yang ditentukan dari span byte yang ditentukan ke stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asynchronous menulis urutan byte ke stream saat ini, memajukan posisi saat ini dalam stream sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Secara asynchronous menulis urutan byte ke stream saat ini, memajukan posisi saat ini dalam stream sebesar jumlah byte yang ditulis, dan memantau permintaan pembatalan. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Jika mode pembungkus adalah biner, menulis ke stream nilai unsigned 8-bit yang ditentukan, jika tidak mengonversinya ke tipe char_type lalu menulis hasilnya ke stream. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Null](../stream/null/) | Sebuah stream tanpa penyimpanan dasar. |

## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Lihat Juga

* Kelas [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Ruang Nama [System::IO](../)
* Library [Aspose.Slides](../../)