---
title: Cookie
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili cookie HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 1
url: /id/system.net/cookie/
---
## Kelas Cookie

Mewakili cookie HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class Cookie : public System::Object
```

## Metode

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Membuat salinan dari instance saat ini. |
|  [Cookie](./cookie/)() | Membuat sebuah instance baru. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Membuat sebuah instance baru. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Membuat sebuah instance baru. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Membuat sebuah instance baru. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Mendapatkan nilai atribut 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Mendapatkan nilai atribut 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Mendapatkan nilai atribut 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Mendapatkan nilai atribut 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Mendapatkan nilai yang menunjukkan apakah domain implisit. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Mengembalikan kunci domain. |
| **bool** [get_Expired](./get_expired/)() | Mendapatkan nilai yang menunjukkan apakah cookie telah kedaluwarsa. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Mendapatkan nilai atribut 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Mendapatkan nilai atribut 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Mendapatkan nama cookie. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Mendapatkan nilai atribut 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Mengembalikan nilai yang menunjukkan apakah spesifikasi cookie adalah 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Mendapatkan nilai atribut 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Mengembalikan koleksi nilai atribut 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Mendapatkan nilai atribut 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Mengembalikan waktu saat cookie dibuat. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Mendapatkan nilai cookie. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Mendapatkan spesifikasi cookie. |
| **int32_t** [get_Version](./get_version/)() const | Mendapatkan nilai atribut '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Metode ini dipanggil oleh metode lain untuk menetapkan nama metode. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan objek tipe nilai dengan nullptr berdasarkan referensi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Menetapkan nilai atribut 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Menetapkan nilai atribut 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Menetapkan nilai atribut 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Menetapkan nilai atribut 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Menetapkan nilai yang menunjukkan apakah domain implisit. |
| void [set_Expired](./set_expired/)(**bool**) | Menetapkan nilai yang menunjukkan apakah cookie kedaluwarsa. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Menetapkan nilai atribut 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Menetapkan nilai atribut 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Menetapkan nama cookie. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Menetapkan nilai atribut 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Menetapkan nilai atribut 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Menetapkan nilai atribut 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Menetapkan nilai cookie. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Menetapkan spesifikasi cookie. |
| void [set_Version](./set_version/)(**int32_t**) | Menetapkan nilai atribut '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Menyerialisasi instance saat ini ke representasi string. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Memverifikasi dan menetapkan nilai atribut default. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung weak reference. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung weak reference. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Field | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Nama atribut 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Nama atribut 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Nama atribut 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Nama atribut 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Pemisor yang digunakan untuk memisahkan nama dan nilai sebuah atribut. |
| static [ExpiresAttributeName](./expiresattributename/) | Nama atribut 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Nama atribut 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Nama atribut 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Versi maksimum yang didukung. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Representasi string dari versi maksimum yang didukung. |
| static [PathAttributeName](./pathattributename/) | Nama atribut 'Path'. |
| static [PortAttributeName](./portattributename/) | Nama atribut 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Array yang berisi pemisah untuk nilai atribut 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | Simbol yang digunakan untuk membungkus bagian atribut. |
| static [ReservedToName](./reservedtoname/) | Nilai yang dicadangkan untuk nama cookie. |
| static [ReservedToValue](./reservedtovalue/) | Nilai yang dicadangkan untuk nilai cookie. |
| static [SecureAttributeName](./secureattributename/) | Nama atribut 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Pemisah atribut. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Awalan nama atribut khusus. |
| static [VersionAttributeName](./versionattributename/) | Nama atribut '[Version](../../system/version/)'. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [System::Net](../)
* Perpustakaan [Aspose.Slides](../../)