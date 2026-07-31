---
title: HttpWebRequest
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili permintaan web HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 274
url: /id/system.net/httpwebrequest/
---
## HttpWebRequest kelas


Mewakili permintaan web HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Abort](./abort/)() override | Membatalkan permintaan saat ini. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Menambahkan header '[Range](../../system/range/)' ke permintaan saat ini. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Menambahkan header '[Range](../../system/range/)' ke permintaan saat ini. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Memulai operasi asynchronous untuk mendapatkan aliran (stream) guna menulis data ke sumber daya. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Memulai permintaan asynchronous untuk sumber daya. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Membuat instance baru dari kelas [WebRequest](../webrequest/) menggunakan URI yang ditentukan. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Membuat instance baru dari kelas [WebRequest](../webrequest/) menggunakan URI yang ditentukan. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Membuat keturunan [WebRequest](../webrequest/) untuk skema URI yang ditentukan. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Membuat instance baru dari kelas [WebRequest](../webrequest/) menggunakan URI yang ditentukan. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Membuat instance baru dari kelas [WebRequest](../webrequest/) menggunakan URI yang ditentukan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Menunggu sampai operasi asynchronous yang ditentukan untuk mendapatkan aliran selesai. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Menunggu sampai permintaan asynchronous yang ditentukan untuk sumber daya selesai. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Mengambil nilai header HTTP 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Mengambil nilai yang menunjukkan apakah permintaan harus mengikuti pengalihan. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Mengambil nilai yang menunjukkan apakah data yang diterima dari sumber daya harus di-buffer. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Mengambil nilai yang menunjukkan apakah buffering diaktifkan untuk mengirim data. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Mengambil kebijakan cache. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Mengambil koleksi sertifikat yang terkait dengan permintaan saat ini. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Mengambil nama grup koneksi. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Mengambil jumlah byte data permintaan yang akan dikirim. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Mengambil tipe MIME permintaan. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Mengambil batas waktu menunggu hingga kode status 100-Continue diterima. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Mengambil kontainer cookie yang terkait dengan permintaan web saat ini. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Mengambil informasi otentikasi yang terkait dengan permintaan saat ini. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Mengambil proxy HTTP global. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Mengembalikan nilai yang menunjukkan apakah respons telah diterima. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Mengambil koleksi header HTTP. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Mengambil nilai yang menunjukkan apakah permintaan saat ini harus menyertakan header 'Keep-Alive'. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Mengambil jumlah maksimum pengalihan yang diizinkan. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Mengambil metode HTTP. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Mengambil nilai yang menunjukkan apakah permintaan harus pra-otentikasi. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Mengambil daftar prefix. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Mengambil proxy HTTP. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Mengambil nilai header 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Mengembalikan URI permintaan. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Mengambil nilai yang menunjukkan apakah data harus dikirim dalam segmen. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Mengembalikan service point yang mewakili koneksi jaringan ke sumber daya. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Mengembalikan nilai yang menunjukkan apakah permintaan saat ini dapat menggunakan kontainer cookie. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Mengambil durasi waktu dalam milidetik setelah mana permintaan akan kedaluwarsa. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Mengambil nilai yang menunjukkan apakah properti 'Credential' sama dengan properti 'DefaultCredentials'. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Mengambil nilai header 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mengambil struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan pembuatan hash untuk objek khusus. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Mengembalikan aliran untuk menulis data ke sumber daya. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Mengembalikan respons web yang terkait dengan permintaan web saat ini. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mengambil tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Membuat instance baru. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Mendaftarkan keturunan [WebRequest](../webrequest/) untuk URI yang ditentukan. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Mengatur nilai header HTTP 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Mengatur nilai yang menunjukkan apakah permintaan harus mengikuti pengalihan. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Mengatur nilai yang menunjukkan apakah data yang diterima dari sumber daya harus di-buffer. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Mengatur nilai yang menunjukkan apakah buffering diaktifkan untuk mengirim data. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Mengatur kebijakan cache. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Mengatur koleksi sertifikat yang terkait dengan permintaan saat ini. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Mengatur nama grup koneksi. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Mengatur jumlah byte data permintaan yang akan dikirim. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Mengatur tipe MIME permintaan. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Mengatur batas waktu menunggu hingga kode status 100-Continue diterima. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Mengatur kontainer cookie yang terkait dengan permintaan web saat ini. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Mengatur informasi otentikasi yang terkait dengan permintaan saat ini. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Mengatur proxy HTTP global. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Mengatur koleksi header HTTP. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Mengatur nilai yang menunjukkan apakah permintaan saat ini harus menyertakan header 'Keep-Alive'. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Mengatur jumlah maksimum pengalihan yang diizinkan. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Mengatur metode HTTP. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Mengatur nilai yang menunjukkan apakah permintaan harus pra-otentikasi. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Mengatur daftar prefix. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Mengatur versi HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Mengatur proxy HTTP. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Mengatur nilai header 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Mengatur nilai yang menunjukkan apakah data harus dikirim dalam segmen. |
| void [set_Timeout](./set_timeout/)(int) override | Mengatur durasi waktu dalam milidetik setelah mana permintaan akan kedaluwarsa. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Mengatur durasi waktu dalam milidetik setelah mana permintaan akan kedaluwarsa. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Mengatur nilai yang menunjukkan apakah properti 'Credential' sama dengan properti 'DefaultCredentials'. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Mengatur nilai header 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mengambil nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [WebRequest](../webrequest/)
* Ruang Nama [System::Net](../)
* Library [Aspose.Slides](../../)