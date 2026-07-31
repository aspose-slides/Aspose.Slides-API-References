---
title: XmlWriterSettings
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan seperangkat fitur untuk didukung pada objek XmlWriter yang dibuat oleh metode XmlWriter::Create."
type: docs
weight: 586
url: /id/system.xml/xmlwritersettings/
---
## XmlWriterSettings kelas


Menentukan seperangkat fitur untuk didukung pada objek [XmlWriter](../xmlwriter/) yang dibuat oleh metode [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Membuat salinan dari instance [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Mengembalikan nilai yang menunjukkan apakah penulis XML harus memeriksa agar semua karakter dalam dokumen mematuhi bagian \"2.2 Characters\" dari W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Mengembalikan nilai yang menunjukkan apakah [XmlWriter](../xmlwriter/) juga harus menutup aliran dasar atau TextWriter ketika metode [XmlWriter::Close](../xmlwriter/close/) dipanggil. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Mengembalikan tingkat kepatuhan yang diperiksa penulis XML terhadap output XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Mengembalikan nilai yang menunjukkan apakah [XmlWriter](../xmlwriter/) tidak meloloskan atribut URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Mengembalikan tipe enkoding teks yang akan digunakan. |
| **bool** [get_Indent](./get_indent/)() | Mengembalikan nilai yang menunjukkan apakah elemen harus diindentasi. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Mengembalikan string karakter yang digunakan saat mengindentasi. Pengaturan ini digunakan ketika nilai [XmlWriterSettings::set_Indent](./set_indent/) disetel ke **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Mengembalikan nilai yang menunjukkan apakah [XmlWriter](../xmlwriter/) harus menghapus deklarasi ruang nama duplikat saat menulis konten XML. Perilaku default adalah penulis mengeluarkan semua deklarasi ruang nama yang ada di resolver ruang nama penulis. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Mengembalikan string karakter yang digunakan untuk pemutusan baris. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Mengembalikan nilai yang menunjukkan apakah harus menormalkan pemutusan baris dalam output. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Mengembalikan nilai yang menunjukkan apakah atribut ditulis pada baris baru. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Mengembalikan nilai yang menunjukkan apakah deklarasi XML dihilangkan. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Mengembalikan metode yang digunakan untuk menyerialkan output [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Mengembalikan nilai yang menunjukkan apakah [XmlWriter](../xmlwriter/) akan menambahkan tag penutup ke semua tag elemen yang tidak tertutup ketika metode [XmlWriter::Close](../xmlwriter/close/) dipanggil. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan C# lock() untuk mengunci. Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan nilai tipe referensi objek dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama dengan nilai yang ditentukan. |
| void [Reset](./reset/)() | Mengatur ulang anggota kelas pengaturan ke nilai default mereka. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Menetapkan nilai yang menunjukkan apakah penulis XML harus memeriksa agar semua karakter dalam dokumen mematuhi bagian \"2.2 Characters\" dari W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Menetapkan nilai yang menunjukkan apakah [XmlWriter](../xmlwriter/) juga harus menutup aliran dasar atau TextWriter ketika metode [XmlWriter::Close](../xmlwriter/close/) dipanggil. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Menetapkan tingkat kepatuhan yang diperiksa penulis XML terhadap output XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Menetapkan nilai yang menunjukkan apakah [XmlWriter](../xmlwriter/) tidak meloloskan atribut URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Menetapkan tipe enkoding teks yang akan digunakan. |
| void [set_Indent](./set_indent/)(**bool**) | Menetapkan nilai yang menunjukkan apakah elemen harus diindentasi. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Menetapkan string karakter yang digunakan saat mengindentasi. Pengaturan ini digunakan ketika nilai [XmlWriterSettings::set_Indent](./set_indent/) disetel ke **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Menetapkan nilai yang menunjukkan apakah [XmlWriter](../xmlwriter/) harus menghapus deklarasi ruang nama duplikat saat menulis konten XML. Perilaku default adalah penulis mengeluarkan semua deklarasi ruang nama yang ada di resolver ruang nama penulis. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Menetapkan string karakter yang digunakan untuk pemutusan baris. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Menetapkan nilai yang menunjukkan apakah harus menormalkan pemutusan baris dalam output. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Menetapkan nilai yang menunjukkan apakah atribut ditulis pada baris baru. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Menetapkan nilai yang menunjukkan apakah deklarasi XML dihilangkan. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Menetapkan nilai yang menunjukkan apakah [XmlWriter](../xmlwriter/) akan menambahkan tag penutup ke semua tag elemen yang tidak tertutup ketika metode [XmlWriter::Close](../xmlwriter/close/) dipanggil. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n sebagai weak pointer (bukan shared). Memungkinkan beralih pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() untuk membuka kunci. Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung weak reference. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung weak reference. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Menginisialisasi instance baru dari kelas [XmlWriterSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Tipe Alias

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance dari kelas ini. |

## Catatan



Objek dari kelas ini harus dialokasikan hanya menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. 

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)