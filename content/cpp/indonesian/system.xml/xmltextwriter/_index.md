---
title: XmlTextWriter
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili penulis yang menyediakan cara cepat, tidak ter-cache, hanya maju untuk menghasilkan aliran atau file yang berisi data XML yang mematuhi W3C Extensible Markup Language (XML) 1.0 dan rekomendasi Namespaces in XML.
type: docs
weight: 521
url: /id/system.xml/xmltextwriter/
---
## XmlTextWriter kelas

Mewakili penulis yang menyediakan cara cepat, tidak ter-cache, hanya maju untuk menghasilkan aliran atau file yang berisi data XML yang mematuhi W3C Extensible Markup Language (XML) 1.0 dan rekomendasi Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Close](./close/)() override | Menutup aliran ini dan aliran yang mendasarinya. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan nama file yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan nama file dan objek [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan stream yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan stream dan objek [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan TextWriter yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan TextWriter dan objek [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan [Text::StringBuilder](../../system.text/stringbuilder/) yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan objek [Text::StringBuilder](../../system.text/stringbuilder/) dan [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan objek [XmlWriter](../xmlwriter/) yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Membuat sebuah instance [XmlWriter](../xmlwriter/) baru menggunakan objek [XmlWriter](../xmlwriter/) dan [XmlWriterSettings](../xmlwritersettings/) yang ditentukan. |
| void [Dispose](../xmlwriter/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh instance [XmlWriter](../xmlwriter/) kelas saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| void [Flush](./flush/)() override | Membuang apa pun yang ada di buffer ke stream yang mendasarinya dan juga membuang stream yang mendasarinya. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Mengembalikan objek stream yang mendasarinya. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Menunjukkan bagaimana output diformat. |
| **int32_t** [get_Indentation](./get_indentation/)() | Mengembalikan berapa banyak IndentChars yang akan ditulis untuk setiap tingkat dalam hierarki ketika [XmlTextWriter::set_Formatting](./set_formatting/) disetel ke [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Mengembalikan karakter yang digunakan untuk indentasi ketika [XmlTextWriter::set_Formatting](./set_formatting/) disetel ke [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Mengembalikan nilai yang menunjukkan apakah mendukung namespace. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Mengembalikan karakter yang digunakan untuk mengutip nilai atribut. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Mengembalikan objek [XmlWriterSettings](../xmlwritersettings/) yang digunakan untuk membuat instance [XmlWriter](../xmlwriter/) ini. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Mengembalikan status penulis. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Mengembalikan ruang lingkup **xml:lang** saat ini. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Mengembalikan XmlSpace yang mewakili ruang lingkup **xml:space** saat ini. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Mengembalikan awalan terdekat yang didefinisikan dalam ruang lingkup namespace saat ini untuk URI namespace. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Menunjukkan bagaimana output diformat. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Mengatur berapa banyak IndentChars yang akan ditulis untuk setiap tingkat dalam hierarki ketika [XmlTextWriter::set_Formatting](./set_formatting/) disetel ke [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Mengatur karakter yang digunakan untuk indentasi ketika [XmlTextWriter::set_Formatting](./set_formatting/) disetel ke [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Mengatur nilai yang menunjukkan apakah dukungan namespace diaktifkan. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Mengatur karakter yang digunakan untuk mengutip nilai atribut. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer di dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Ketika dioverride dalam kelas turunan, menulis semua atribut yang ditemukan pada posisi saat ini dalam [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ketika dioverride dalam kelas turunan, menulis sebuah atribut dengan nama lokal, URI namespace, dan nilai yang ditentukan. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ketika dioverride dalam kelas turunan, menulis atribut dengan nama lokal dan nilai yang ditentukan. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ketika dioverride dalam kelas turunan, menulis atribut dengan awalan, nama lokal, URI namespace, dan nilai yang ditentukan. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Mengkodekan byte biner yang ditentukan sebagai base64 dan menulis teks hasilnya. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Mengkodekan byte biner yang ditentukan sebagai binhex dan menulis teks hasilnya. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Menulis blok **...** yang berisi teks yang ditentukan. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Memaksa pembuatan entitas karakter untuk nilai karakter Unicode yang ditentukan. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Menulis teks satu buffer pada satu waktu. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Menulis komentar **** yang berisi teks yang ditentukan. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Menulis deklarasi DOCTYPE dengan nama dan atribut opsional yang ditentukan. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menulis elemen dengan nama lokal dan nilai yang ditentukan. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menulis elemen dengan nama lokal, URI namespace, dan nilai yang ditentukan. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menulis elemen dengan awalan, nama lokal, URI namespace, dan nilai yang ditentukan. |
| void [WriteEndAttribute](./writeendattribute/)() override | Menutup pemanggilan [XmlTextWriter::WriteStartAttribute](./writestartattribute/) sebelumnya. |
| void [WriteEndDocument](./writeenddocument/)() override | Menutup semua elemen atau atribut yang terbuka dan mengembalikan penulis ke keadaan Start. |
| void [WriteEndElement](./writeendelement/)() override | Menutup satu elemen dan mengeluarkan ruang lingkup namespace yang bersesuaian. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Menulis referensi entitas sebagai **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Menutup satu elemen dan mengeluarkan ruang lingkup namespace yang bersesuaian. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Menulis nama yang ditentukan, memastikan itu adalah nama yang valid menurut [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Menulis nama yang ditentukan, memastikan itu adalah **NmToken** yang valid menurut [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Ketika dioverride dalam kelas turunan, menyalin semua dari pembaca ke penulis dan memindahkan pembaca ke awal saudara berikutnya. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Menyalin semua dari objek XPathNavigator ke penulis. Posisi XPathNavigator tetap tidak berubah. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Menulis instruksi pemrosesan dengan spasi antara nama dan teks sebagai berikut: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Menulis nama yang memenuhi namespace. Metode ini mencari awalan yang berada dalam ruang lingkup untuk namespace yang diberikan. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Menulis markup mentah secara manual dari buffer karakter. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Menulis markup mentah secara manual dari string. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Menulis awal atribut. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Menulis awal atribut dengan nama lokal dan URI namespace yang ditentukan. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Menulis awal atribut dengan nama lokal yang ditentukan. |
| void [WriteStartDocument](./writestartdocument/)() override | Menulis deklarasi XML dengan versi "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Menulis deklarasi XML dengan versi "1.0" dan atribut standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Menulis tag pembuka yang ditentukan dan mengaitkannya dengan namespace dan awalan yang diberikan. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ketika dioverride dalam kelas turunan, menulis tag pembuka yang ditentukan dan mengaitkannya dengan namespace yang diberikan. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Ketika dioverride dalam kelas turunan, menulis tag pembuka dengan nama lokal yang ditentukan. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Menulis konten teks yang diberikan. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Membuat dan menulis entitas karakter surrogate untuk pasangan karakter surrogate. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Menulis nilai objek. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Menulis nilai [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Menulis nilai [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Menulis nilai [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Menulis nilai [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Menulis nilai [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Menulis angka floating-point presisi tunggal. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Menulis nilai [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Menulis nilai [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Menulis nilai [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Menulis spasi putih yang diberikan. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Membuat instance kelas [XmlTextWriter](./) menggunakan stream dan encoding yang ditentukan. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Membuat instance kelas [XmlTextWriter](./) menggunakan file yang ditentukan. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Membuat instance kelas [XmlTextWriter](./) menggunakan TextWriter yang ditentukan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance kelas ini. |

## Catatan

Disarankan untuk menggunakan kelas [XmlWriter](../xmlwriter/) sebagai gantinya.  

Objek dari kelas ini sebaiknya hanya dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan error runtime dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer tersebut untuk meneruskan ke fungsi sebagai argumen.  

## Lihat Juga

* Kelas [XmlWriter](../xmlwriter/)
* Namespace [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)