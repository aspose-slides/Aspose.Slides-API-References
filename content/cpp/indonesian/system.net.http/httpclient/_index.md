---
title: HttpClient
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili kelas dasar klien HTTP untuk mengirim permintaan dan menerima respons. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini dengan pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 27
url: /id/system.net.http/httpclient/
---
## Kelas HttpClient


Mewakili kelas dasar klien HTTP untuk mengirim permintaan dan menerima respons. Objek dari kelas ini hanya dapat dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class HttpClient : public System::Net::Http::HttpMessageInvoker
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [CancelPendingRequests](./cancelpendingrequests/)() | Membatalkan semua permintaan yang tertunda. |
| void [Dispose](../httpmessageinvoker/dispose/)() override | Membuang instansi saat ini. Metode ini juga membuang handler jika diperlukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_BaseAddress](./get_baseaddress/)() | Mendapatkan alamat dasar sumber daya yang digunakan untuk mengirim permintaan. |
| [System::SharedPtr](../../system/sharedptr/)\<[Headers::HttpRequestHeaders](../../system.net.http.headers/httprequestheaders/)\> [get_DefaultRequestHeaders](./get_defaultrequestheaders/)() | Mendapatkan header yang dikirim dengan setiap permintaan. |
| **int64_t** [get_MaxResponseContentBufferSize](./get_maxresponsecontentbuffersize/)() | Mendapatkan jumlah maksimum byte dari konten respons. |
| [TimeSpan](../../system/timespan/) [get_Timeout](./get_timeout/)() | Mendapatkan rentang waktu yang harus ditunggu sebelum permintaan kedaluwarsa. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing pada objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpClient](./httpclient/)() | Membuat instansi baru. |
|  [HttpClient](./httpclient/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>) | Membuat instansi baru. |
|  [HttpClient](./httpclient/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>, **bool**) | Membuat instansi baru. |
|  [HttpMessageInvoker](../httpmessageinvoker/httpmessageinvoker/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>) | Membuat instansi baru. |
|  [HttpMessageInvoker](../httpmessageinvoker/httpmessageinvoker/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>, **bool**) | Membuat instansi baru. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merepresentasikan instansi dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan objek tipe nilai dengan nullptr menggunakan referensi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama dengan nilai yang ditentukan. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](../httpresponsemessage/)\> [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>, [HttpCompletionOption](../httpcompletionoption/)) | Mengirim permintaan HTTP yang ditentukan. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](../httpresponsemessage/)\> [Send](../httpmessageinvoker/send/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>) | Mengirim permintaan yang ditentukan. |
| void [set_BaseAddress](./set_baseaddress/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Mengatur alamat dasar sumber daya yang digunakan untuk mengirim permintaan. |
| void [set_MaxResponseContentBufferSize](./set_maxresponsecontentbuffersize/)(**int64_t**) | Mengatur jumlah maksimum byte dari konten respons. |
| void [set_Timeout](./set_timeout/)([TimeSpan](../../system/timespan/)) | Mengatur rentang waktu yang harus ditunggu sebelum permintaan kedaluwarsa. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [HttpMessageInvoker](../httpmessageinvoker/)
* Ruang Nama [System::Net::Http](../)
* Pustaka [Aspose.Slides](../../)