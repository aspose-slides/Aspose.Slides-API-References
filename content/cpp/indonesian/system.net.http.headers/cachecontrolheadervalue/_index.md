---
title: CacheControlHeaderValue
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili nilai dari header 'Cache-Control'. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 14
url: /id/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue kelas

Mewakili nilai dari header 'Cache-Control'. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Membuat sebuah instance baru. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Mengembalikan koleksi token ekstensi cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Mendapatkan nilai umur maksimum dalam detik yang menentukan periode di mana klien akan menerima respons. |
| **bool** [get_MaxStale](./get_maxstale/)() | Mendapatkan nilai yang menentukan apakah klien akan menerima respons yang kedaluwarsa. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Mendapatkan nilai dalam detik yang menentukan periode di mana klien akan menerima respons yang kedaluwarsa. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Mendapatkan nilai yang menentukan masa hidup kesegaran. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Mendapatkan nilai yang menentukan apakah server memerlukan revalidasi entri cache ketika menjadi usang. |
| **bool** [get_NoCache](./get_nocache/)() | Mendapatkan nilai yang menentukan apakah klien akan menerima respons yang di-cache. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Mengembalikan koleksi nama bidang dalam arahan 'no-cache' pada header 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Mendapatkan nilai yang menentukan apakah cache tidak boleh menyimpan bagian apa pun dari permintaan atau respons HTTP. |
| **bool** [get_NoTransform](./get_notransform/)() | Mendapatkan nilai yang menentukan apakah cache atau proxy tidak boleh mengubah bagian apa pun dari badan entitas. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Mendapatkan nilai yang menentukan apakah klien harus hanya menggunakan entri yang di-cache. |
| **bool** [get_Private](./get_private/)() | Mendapatkan nilai yang menentukan apakah pesan respons HTTP atau bagiannya ditujukan untuk satu pengguna dan tidak boleh di-cache oleh cache bersama. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Mengembalikan koleksi nama bidang dalam arahan 'private' pada header 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Mendapatkan nilai yang menentukan apakah server memerlukan revalidasi entri cache ketika menjadi usang untuk cache agen pengguna bersama. |
| **bool** [get_Public](./get_public/)() | Mendapatkan nilai yang menentukan apakah respons HTTP dapat di-cache oleh cache apa pun. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Mendapatkan nilai umur maksimum bersama dalam detik yang menggantikan arahan 'max-age' pada header 'Cache-Control' atau header 'Expires' untuk cache bersama. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Mengonversi string yang diberikan dari indeks yang ditentukan menjadi sebuah instance dari kelas [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Mengonversi string yang diberikan menjadi sebuah instance dari kelas [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Menetapkan nilai umur maksimum dalam detik yang menentukan periode di mana klien akan menerima respons. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Menetapkan nilai yang menentukan apakah klien akan menerima respons yang kedaluwarsa. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Menetapkan nilai dalam detik yang menentukan periode di mana klien akan menerima respons yang kedaluwarsa. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Menetapkan nilai yang menentukan masa hidup kesegaran. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Menetapkan nilai yang menentukan apakah server memerlukan revalidasi entri cache ketika menjadi usang. |
| void [set_NoCache](./set_nocache/)(**bool**) | Menetapkan nilai yang menentukan apakah klien akan menerima respons yang di-cache. |
| void [set_NoStore](./set_nostore/)(**bool**) | Menetapkan nilai yang menentukan apakah cache tidak boleh menyimpan bagian apa pun dari permintaan atau respons HTTP. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Menetapkan nilai yang menentukan apakah cache atau proxy tidak boleh mengubah bagian apa pun dari badan entitas. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Menetapkan nilai yang menentukan apakah klien harus hanya menggunakan entri yang di-cache. |
| void [set_Private](./set_private/)(**bool**) | Menetapkan nilai yang menentukan apakah pesan respons HTTP atau bagiannya ditujukan untuk satu pengguna dan tidak boleh di-cache oleh cache bersama. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Menetapkan nilai yang menentukan apakah server memerlukan revalidasi entri cache ketika menjadi usang untuk cache agen pengguna bersama. |
| void [set_Public](./set_public/)(**bool**) | Menetapkan nilai yang menentukan apakah respons HTTP dapat di-cache oleh cache manapun. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Menetapkan nilai umur maksimum bersama dalam detik yang menggantikan arahan 'max-age' pada header 'Cache-Control' atau header 'Expires' untuk cache bersama. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambahkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Mencoba mengonversi string yang diberikan menjadi sebuah instance dari kelas [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambahkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [ICloneable](../../system/icloneable/)
* Ruang Nama [System::Net::Http::Headers](../)
* Perpustakaan [Aspose.Slides](../../)