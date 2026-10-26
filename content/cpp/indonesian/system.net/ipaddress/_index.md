---
title: IPAddress
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili alamat IP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 326
url: /id/system.net/ipaddress/
---
## IPAddress kelas


Mewakili alamat IP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class IPAddress : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Mengembalikan keluarga alamat. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Mengembalikan nilai yang menunjukkan apakah alamat tersebut adalah alamat IPv4 dan dipetakan ke alamat IPv6. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Mengembalikan nilai yang menunjukkan apakah alamat tersebut adalah alamat IPv6 link-local. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Mengembalikan nilai yang menunjukkan apakah alamat tersebut adalah alamat multicast IPv6 global. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Mengembalikan nilai yang menunjukkan apakah alamat tersebut adalah alamat IPv6 site-local. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Mengembalikan nilai yang menunjukkan apakah alamat tersebut adalah alamat IPv6 Teredo. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Mendapatkan pengidentifikasi cakupan dari alamat IPv6. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Mengembalikan array byte dari alamat IP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Mengembalikan pointer ke implementasi. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Mengonversi urutan byte host yang ditentukan ke urutan byte jaringan yang sesuai. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Mengonversi urutan byte host yang ditentukan ke urutan byte jaringan yang sesuai. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Mengonversi urutan byte host yang ditentukan ke urutan byte jaringan yang sesuai. |
| [IPAddress](./ipaddress/)(**int64_t**) | Membuat instance baru. |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Membuat instance baru. |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Membuat instance baru. |
| [IPAddress](./ipaddress/)() | Membuat instance baru. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Mengembalikan nilai yang menunjukkan apakah alamat yang ditentukan adalah alamat loopback. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Memetakan alamat ke alamat IPv4. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Memetakan alamat ke alamat IPv6. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Mengonversi urutan byte jaringan yang ditentukan ke urutan byte host yang sesuai. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Mengonversi urutan byte jaringan yang ditentukan ke urutan byte host yang sesuai. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Mengonversi urutan byte jaringan yang ditentukan ke urutan byte host yang sesuai. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan turunan dengan menyalin. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan turunan dengan menyalin. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Mengonversi string yang diberikan menjadi instance kelas [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Menetapkan pengidentifikasi cakupan alamat IPv6. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Menetapkan pointer ke implementasi. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Mencoba mengonversi string yang diberikan menjadi instance kelas [IPAddress](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Any](./any/) | Alamat IPv4 yang menunjukkan apakah server harus mendengarkan semua antarmuka jaringan. |
| static [Broadcast](./broadcast/) | Alamat broadcast IPv4. |
| static [IPv6Any](./ipv6any/) | Alamat IPv6 yang menunjukkan apakah server harus mendengarkan semua antarmuka jaringan. |
| static [IPv6Loopback](./ipv6loopback/) | Alamat loopback IPv6. |
| static [IPv6None](./ipv6none/) | Alamat IPv6 yang menunjukkan apakah server tidak boleh mendengarkan antarmuka jaringan apa pun. |
| static [Loopback](./loopback/) | Alamat loopback IPv4. |
| static [None](./none/) | Alamat IPv4 yang menunjukkan apakah server tidak boleh mendengarkan antarmuka jaringan apa pun. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [ImplPtr](./implptr/) | Pointer ke tipe implementasi. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Namespace [System::Net](../)
* Perpustakaan [Aspose.Slides](../../)