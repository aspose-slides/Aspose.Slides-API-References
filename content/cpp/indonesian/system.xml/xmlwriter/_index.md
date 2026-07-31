---
title: XmlWriter
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili penulis yang menyediakan cara cepat, tanpa cache, hanya maju untuk menghasilkan aliran atau berkas yang berisi data XML.
type: docs
weight: 573
url: /id/system.xml/xmlwriter/
---
## XmlWriter kelas

Mewakili penulis yang menyediakan cara cepat, tanpa cache, hanya maju untuk menghasilkan aliran atau berkas yang berisi data XML.

```cpp
class XmlWriter : public System::IDisposable
```

## Metode

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Saat ditimpa dalam kelas turunan, menutup aliran ini dan aliran dasar. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Membuat instance [XmlWriter](./) baru menggunakan nama berkas yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat instance [XmlWriter](./) baru menggunakan nama berkas dan objek [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Membuat instance [XmlWriter](./) baru menggunakan aliran yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat instance [XmlWriter](./) baru menggunakan aliran dan objek [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Membuat instance [XmlWriter](./) baru menggunakan TextWriter yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat instance [XmlWriter](./) baru menggunakan TextWriter dan objek [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Membuat instance [XmlWriter](./) baru menggunakan [Text::StringBuilder](../../system.text/stringbuilder/) yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat instance [XmlWriter](./) baru menggunakan objek [Text::StringBuilder](../../system.text/stringbuilder/) dan [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Membuat instance [XmlWriter](./) baru menggunakan objek [XmlWriter](./) yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat instance [XmlWriter](./) baru menggunakan objek [XmlWriter](./) dan [XmlWriterSettings](../xmlwritersettings/) yang ditentukan. |
| void [Dispose](./dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh instance [XmlWriter](./) saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual void [Flush](./flush/)() | Saat ditimpa dalam kelas turunan, mengosongkan apa pun yang ada di buffer ke aliran dasar dan juga mengosongkan aliran dasar. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Mengembalikan objek [XmlWriterSettings](../xmlwritersettings/) yang digunakan untuk membuat instance [XmlWriter](./) ini. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Saat ditimpa dalam kelas turunan, mendapatkan keadaan penulis. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Saat ditimpa dalam kelas turunan, mendapatkan lingkup **xml:lang** saat ini. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Saat ditimpa dalam kelas turunan, mendapatkan XmlSpace yang mewakili lingkup **xml:space** saat ini. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Saat ditimpa dalam kelas turunan, mengembalikan prefiks terdekat yang didefinisikan dalam lingkup namespace saat ini untuk URI namespace. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengizinkan konstruktor penyalinan pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengizinkan konstruktor penyalinan pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi jumlah referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan jumlah referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan jumlah referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan jumlah referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi jumlah referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Saat ditimpa dalam kelas turunan, menuliskan semua atribut yang ditemukan pada posisi saat ini di [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan atribut dengan nama lokal, URI namespace, dan nilai yang ditentukan. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan atribut dengan nama lokal dan nilai yang ditentukan. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan atribut dengan prefiks, nama lokal, URI namespace, dan nilai yang ditentukan. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Saat ditimpa dalam kelas turunan, mengkodekan byte biner yang ditentukan sebagai Base64 dan menuliskan teks hasilnya. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Saat ditimpa dalam kelas turunan, mengkodekan byte biner yang ditentukan sebagai **BinHex** dan menuliskan teks hasilnya. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Saat ditimpa dalam kelas turunan, menuliskan blok **...** yang berisi teks yang ditentukan. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Saat ditimpa dalam kelas turunan, memaksa pembuatan entitas karakter untuk nilai karakter Unicode yang ditentukan. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Saat ditimpa dalam kelas turunan, menuliskan teks satu buffer pada satu waktu. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Saat ditimpa dalam kelas turunan, menuliskan komentar **** yang berisi teks yang ditentukan. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan deklarasi DOCTYPE dengan nama yang ditentukan dan atribut opsional. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menuliskan elemen dengan nama lokal dan nilai yang ditentukan. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menuliskan elemen dengan nama lokal, URI namespace, dan nilai yang ditentukan. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menuliskan elemen dengan prefiks, nama lokal, URI namespace, dan nilai yang ditentukan. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Saat ditimpa dalam kelas turunan, menutup pemanggilan XmlWriter::WriteStartAttribute(String,String) sebelumnya. |
| virtual void [WriteEndDocument](./writeenddocument/)() | Saat ditimpa dalam kelas turunan, menutup semua elemen atau atribut yang terbuka dan mengembalikan penulis ke keadaan Start. |
| virtual void [WriteEndElement](./writeendelement/)() | Saat ditimpa dalam kelas turunan, menutup satu elemen dan mengeluarkan lingkup namespace yang bersangkutan. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan referensi entitas sebagai **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Saat ditimpa dalam kelas turunan, menutup satu elemen dan mengeluarkan lingkup namespace yang bersangkutan. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan nama yang ditentukan, memastikan bahwa itu adalah nama yang valid menurut rekomendasi W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan nama yang ditentukan, memastikan bahwa itu adalah NmToken yang valid menurut rekomendasi W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Saat ditimpa dalam kelas turunan, menyalin semua dari pembaca ke penulis dan memindahkan pembaca ke awal saudara berikutnya. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Menyalin semua dari objek XPathNavigator ke penulis. Posisi XPathNavigator tetap tidak berubah. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Saat ditimpa dalam kelas turunan, menuliskan instruksi pemrosesan dengan spasi antara nama dan teks seperti berikut: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan nama yang memenuhi namespace. Metode ini mencari prefiks yang berada dalam lingkup untuk namespace yang diberikan. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Saat ditimpa dalam kelas turunan, menuliskan markup mentah secara manual dari buffer karakter. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan markup mentah secara manual dari string. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menuliskan awal atribut dengan nama lokal dan URI namespace yang ditentukan. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan awal atribut dengan prefiks, nama lokal, dan URI namespace yang ditentukan. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Menuliskan awal atribut dengan nama lokal yang ditentukan. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Saat ditimpa dalam kelas turunan, menuliskan deklarasi XML dengan versi "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Saat ditimpa dalam kelas turunan, menuliskan deklarasi XML dengan versi "1.0" dan atribut standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan tag pembuka yang ditentukan dan mengaitkannya dengan namespace yang diberikan. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan tag pembuka yang ditentukan dan mengaitkannya dengan namespace dan prefiks yang diberikan. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan tag pembuka dengan nama lokal yang ditentukan. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menuliskan konten teks yang diberikan. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Saat ditimpa dalam kelas turunan, menghasilkan dan menuliskan entitas karakter surrogate untuk pasangan karakter surrogate. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Menuliskan nilai objek. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Menuliskan nilai [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Menuliskan nilai [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Menuliskan nilai [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Menuliskan nilai [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Menuliskan nilai [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Menuliskan angka titik mengambang presisi tunggal. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Menuliskan nilai [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Menuliskan nilai [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Menuliskan nilai [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Saat ditimpa dalam kelas turunan, menuliskan spasi putih yang diberikan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedef

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke instance kelas ini. |

## Lihat Juga

* Kelas [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Pustaka [Aspose.Slides](../../)