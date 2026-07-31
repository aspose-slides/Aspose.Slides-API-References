---
title: Uri
second_title: Referensi API Aspose.Slides untuk C++
description: "Pengidentifikasi sumber daya terpadu. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 1392
url: /id/system/uri/
---
## Kelas Uri

Pengidentifikasi sumber daya terpadu. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu menjalankan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../smartptr/) dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class Uri : public System::Object
```

## Metode

| Method | Deskripsi |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Menentukan tipe dari nama host yang ditentukan. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Menentukan apakah skema yang ditentukan valid. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Membandingkan objek [Uri](./) yang ditentukan menggunakan aturan perbandingan yang ditentukan. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Menentukan apakah URI yang diwakili oleh objek saat ini dan objek yang ditentukan sama. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Mengonversi string menjadi representasi yang di-escape. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Mengonversi string URI menjadi representasi yang di-escape. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Mendapatkan nilai desimal dari digit heksadesimal. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Mengembalikan jalur absolut dari URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Mengembalikan URI absolut. |
| [String](../string/) [get_Authority](./get_authority/)() const | Mengembalikan nama host dan nomor port untuk server. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Mengembalikan nama host yang tidak di-escape. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Mengembalikan fragmen URI yang di-escape. |
| [String](../string/) [get_Host](./get_host/)() const | Mengembalikan nama host. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Mengembalikan tipe nama host. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Mengembalikan International Domain Name (IDN) dari host. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Menentukan apakah URI yang diwakili oleh objek saat ini bersifat absolut. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Menentukan apakah URI yang diwakili oleh objek saat ini memiliki port default untuk skema URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Menentukan apakah URI yang diwakili oleh objek saat ini adalah file. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Menentukan apakah URI yang diwakili oleh objek saat ini merujuk ke host lokal. |
| **bool** [get_IsUnc](./get_isunc/)() const | Menentukan apakah URI yang diwakili oleh objek saat ini adalah jalur UNC. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Mengembalikan representasi sistem operasi dari nama file yang dirujuk oleh URI yang diwakili oleh objek saat ini. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Mengembalikan string URI yang diberikan ke konstruktor saat objek saat ini dibuat. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Mengembalikan komponen jalur absolut dan query dari URI yang diwakili oleh objek saat ini, dipisahkan dengan tanda tanya (?). |
| **int32_t** [get_Port](./get_port/)() const | Mengembalikan nomor port dari URI yang diwakili oleh objek saat ini. |
| [String](../string/) [get_Query](./get_query/)() const | Mengembalikan informasi query yang termasuk dalam URI yang diwakili oleh objek saat ini. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Mengembalikan skema URI yang diwakili oleh objek saat ini. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Mengembalikan array string yang berisi segmen jalur dari URI yang diwakili oleh objek saat ini. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Menentukan apakah string URI yang diberikan ke konstruktor objek saat ini telah sepenuhnya di-escape. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Mengembalikan nama pengguna, kata sandi, dan informasi pengguna lain yang terkait dengan URI yang diwakili oleh objek saat ini. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Mengembalikan komponen tertentu dari URI yang diwakili oleh objek saat ini menggunakan escape yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Mendapatkan kode hash untuk URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Mengembalikan bagian tertentu dari URI yang diwakili oleh objek saat ini. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi panggilan C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Mengembalikan padanan heksadesimal dari karakter yang ditentukan. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Mengonversi representasi heksadesimal karakter yang ditentukan menjadi karakter. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Menentukan apakah URI yang diwakili oleh objek [Uri](./) saat ini merupakan basis dari URI yang diwakili oleh objek [Uri](./) yang ditentukan. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Menentukan apakah karakter yang ditentukan merupakan digit heksadesimal yang valid. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Menentukan apakah karakter dalam string yang ditentukan pada posisi yang ditentukan ter-encode heksadesimal. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Menunjukkan apakah string yang digunakan untuk membuat [Uri](./) ini sudah terbentuk dengan baik dan tidak perlu di-escape lebih lanjut. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Menentukan apakah string yang ditentukan merupakan URI yang terbentuk dengan baik. |
| void [Lock](../object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Menentukan perbedaan antara dua instance [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Menentukan perbedaan antara URI yang diwakili oleh objek saat ini dan objek [Uri](./) yang ditentukan. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan konstruktor salin pada subclass. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan objek tipe nilai dengan nullptr berdasarkan referensi. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Mengembalikan representasi string dari URI yang diwakili oleh objek saat ini. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Membuat objek [Uri](./) yang mewakili URI yang ditentukan; sebuah argumen menentukan jenis URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Membuat objek [Uri](./) dari objek [Uri](./) yang mewakili URI dasar dan representasi string URI relatif yang ditentukan. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Membuat objek [Uri](./) dari URI dasar dan relatif yang ditentukan. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Melepas escape string yang di-escape. |
| void [Unlock](../object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
|  [Uri](./uri/)(const [String](../string/)\&) | Membuat objek [Uri](./) yang mewakili URI yang ditentukan. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Membuat objek [Uri](./) yang mewakili URI yang ditentukan; sebuah argumen menentukan apakah URI harus di-escape. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Membuat objek [Uri](./) dari objek [Uri](./) yang mewakili URI dasar dan representasi string URI relatif; sebuah argumen menentukan apakah URI harus di-escape. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Membuat objek [Uri](./) yang mewakili URI yang ditentukan; sebuah argumen menentukan jenis URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Membuat objek [Uri](./) dari URI dasar dan relatif yang ditentukan. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Membuat objek [Uri](./) dari URI dasar dan relatif yang ditentukan. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Menentukan karakter yang memisahkan skema protokol komunikasi dari bagian alamat [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Menentukan bahwa [Uri](./) adalah pointer ke sebuah file. |
| static [UriSchemeFtp](./urischemeftp/) | Menentukan bahwa [Uri](./) diakses melalui File Transfer Protocol. |
| static [UriSchemeGopher](./urischemegopher/) | Menentukan bahwa [Uri](./) diakses melalui protokol Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Menentukan bahwa [Uri](./) diakses melalui Hypertext Transfer Protocol. |
| static [UriSchemeHttps](./urischemehttps/) | Menentukan bahwa [Uri](./) diakses melalui Secure Hypertext Transfer Protocol. |
| static [UriSchemeMailto](./urischememailto/) | Menentukan bahwa [Uri](./) adalah alamat email dan diakses melalui Simple Mail Transport Protocol. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Menentukan bahwa [Uri](./) diakses melalui skema NetPipe yang digunakan oleh [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Menentukan bahwa [Uri](./) diakses melalui skema NetTcp yang digunakan oleh [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Menentukan bahwa [Uri](./) adalah grup berita internet dan diakses melalui Network News Transport Protocol. |
| static [UriSchemeNntp](./urischemenntp/) | Menentukan bahwa [Uri](./) adalah grup berita internet dan diakses melalui Network News Transport Protocol. |

## Catatan

```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## Lihat Juga

* Kelas [Object](../object/)
* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)