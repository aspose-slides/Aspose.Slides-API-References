---
title: HttpResponseMessage
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pesan respons HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer tersebut untuk melewatkannya ke fungsi sebagai argumen."
type: docs
weight: 118
url: /id/system.net.http/httpresponsemessage/
---
## HttpResponseMessage kelas


Represents an HTTP response message. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpResponseMessage : public System::IDisposable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Dispose](./dispose/)() override | Membuang instance saat ini. Metode ini juga membuang konten respons HTTP. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](./)\> [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | Memeriksa kode status. HttpRequestException akan dilemparkan ketika kode status tidak termasuk dalam 2xx. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\> [get_Content](./get_content/)() const | Mengambil konten respons HTTP. |
| [System::SharedPtr](../../system/sharedptr/)\<[Headers::HttpResponseHeaders](../../system.net.http.headers/httpresponseheaders/)\> [get_Headers](./get_headers/)() const | Mengembalikan header konten HTTP. |
| **bool** [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | Memeriksa apakah kode status menunjukkan bahwa tindakan yang diminta oleh klien telah diterima, dipahami, dan diterima. |
| [String](../../system/string/) [get_ReasonPhrase](./get_reasonphrase/)() const | Mengambil Reason-Phrase yang dikirim oleh server bersama dengan kode status. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\> [get_RequestMessage](./get_requestmessage/)() const | Mengambil pesan permintaan HTTP. |
| [HttpStatusCode](../../system.net/httpstatuscode/) [get_StatusCode](./get_statuscode/)() const | Mengambil kode status HTTP. |
| [System::Version](../../system/version/) [get_Version](./get_version/)() const | Mengambil versi HTTP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mengambil struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mengambil tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpResponseMessage](./httpresponsemessage/)() | Membuat instance baru. |
|  [HttpResponseMessage](./httpresponsemessage/)([HttpStatusCode](../../system.net/httpstatuscode/)) | Membuat instance baru. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor ke subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor ke subkelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Content](./set_content/)([System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\>) | Mengatur konten respons HTTP. |
| void [set_ReasonPhrase](./set_reasonphrase/)([String](../../system/string/)) | Mengatur Reason-Phrase yang dikirim oleh server bersama dengan kode status. |
| void [set_RequestMessage](./set_requestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>) | Mengatur pesan permintaan HTTP. |
| void [set_StatusCode](./set_statuscode/)([HttpStatusCode](../../system.net/httpstatuscode/)) | Mengatur kode status HTTP. |
| void [set_Version](./set_version/)([System::Version](../../system/version/)) | Mengatur versi HTTP. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mengambil nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [IDisposable](../../system/idisposable/)
* Ruang Nama [System::Net::Http](../)
* Pustaka [Aspose.Slides](../../)