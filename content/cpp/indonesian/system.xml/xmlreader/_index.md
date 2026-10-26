---
title: XmlReader
second_title: Aspose.Slides for C++ Referensi API
description: Mewakili pembaca yang menyediakan akses cepat, tanpa cache, hanya maju ke data XML.
type: docs
weight: 430
url: /id/system.xml/xmlreader/
---
## XmlReader kelas

Mewakili pembaca yang menyediakan akses cepat, tidak ter-cache, hanya maju ke data XML.

```cpp
class XmlReader : public System::IDisposable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual void [Close](./close/)() | Saat ditimpa dalam kelas turunan, mengubah [XmlReader::get_ReadState](./get_readstate/) menjadi [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Membuat instance [XmlReader](./) baru dengan URI yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](./) baru dengan menggunakan URI dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](./) baru dengan menggunakan URI, pengaturan, dan informasi konteks yang ditentukan untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Membuat instance [XmlReader](./) baru menggunakan stream yang ditentukan dengan pengaturan default. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](./) baru dengan stream dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Membuat instance [XmlReader](./) baru dengan stream yang ditentukan, URI dasar, dan pengaturan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](./) baru dengan stream yang ditentukan, pengaturan, dan informasi konteks untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Membuat instance [XmlReader](./) baru dengan menggunakan pembaca teks yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](./) baru dengan menggunakan pembaca teks dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Membuat instance [XmlReader](./) baru dengan menggunakan pembaca teks, pengaturan, dan URI dasar yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](./) baru dengan menggunakan pembaca teks, pengaturan, dan informasi konteks untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Membuat instance [XmlReader](./) baru dengan menggunakan pembaca XML dan pengaturan yang ditentukan. |
| void [Dispose](./dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh instance [XmlReader](./) saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | Saat ditimpa dalam kelas turunan, mendapatkan jumlah atribut pada node saat ini. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Saat ditimpa dalam kelas turunan, mendapatkan URI dasar dari node saat ini. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Mengembalikan nilai yang menunjukkan apakah [XmlReader](./) mengimplementasikan metode pembacaan konten biner. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Mengembalikan nilai yang menunjukkan apakah [XmlReader](./) mengimplementasikan metode [XmlReader::ReadValueChunk](./readvaluechunk/). |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | Mengembalikan nilai yang menunjukkan apakah pembaca ini dapat mengurai dan menyelesaikan entitas. |
| virtual **int32_t** [get_Depth](./get_depth/)() | Saat ditimpa dalam kelas turunan, mendapatkan kedalaman node saat ini dalam dokumen XML. |
| virtual **bool** [get_EOF](./get_eof/)() | Saat ditimpa dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah pembaca berada pada akhir stream. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Mengembalikan nilai yang menunjukkan apakah node saat ini memiliki atribut apa pun. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | Saat ditimpa dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah node saat ini dapat memiliki nilai [XmlReader::get_Value](./get_value/). |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | Saat ditimpa dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah node saat ini adalah atribut yang dihasilkan dari nilai default yang didefinisikan dalam DTD atau skema. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Saat ditimpa dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah node saat ini adalah elemen kosong (misalnya, **<MyElement/>**). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Saat ditimpa dalam kelas turunan, mendapatkan nama lokal node saat ini. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Saat ditimpa dalam kelas turunan, mendapatkan nama yang memenuhi syarat (qualified) dari node saat ini. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Saat ditimpa dalam kelas turunan, mendapatkan URI namespace (sebagaimana didefinisikan dalam spesifikasi Namespace W3C) dari node tempat pembaca berada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Saat ditimpa dalam kelas turunan, mendapatkan [XmlNameTable](../xmlnametable/) yang terkait dengan implementasi ini. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | Saat ditimpa dalam kelas turunan, mendapatkan tipe node saat ini. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Saat ditimpa dalam kelas turunan, mendapatkan prefiks namespace yang terkait dengan node saat ini. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | Saat ditimpa dalam kelas turunan, mendapatkan karakter tanda kutip yang digunakan untuk mengelilingi nilai node atribut. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | Saat ditimpa dalam kelas turunan, mendapatkan status pembaca. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Mengembalikan informasi skema yang telah diberikan ke node saat ini sebagai hasil validasi skema. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | Mengembalikan objek [XmlReaderSettings](../xmlreadersettings/) yang digunakan untuk membuat instance [XmlReader](./) ini. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | Saat ditimpa dalam kelas turunan, mendapatkan nilai teks dari node saat ini. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Mengembalikan tipe untuk node saat ini. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Saat ditimpa dalam kelas turunan, mendapatkan ruang lingkup **xml:lang** saat ini. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Saat ditimpa dalam kelas turunan, mendapatkan ruang lingkup **xml:space** saat ini. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | Saat ditimpa dalam kelas turunan, mendapatkan nilai atribut dengan nilai [XmlReader::get_Name](./get_name/) yang ditentukan. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Saat ditimpa dalam kelas turunan, mendapatkan nilai atribut dengan nilai [XmlReader::get_LocalName](./get_localname/) dan [XmlReader::get_NamespaceURI](./get_namespaceuri/) yang ditentukan. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | Saat ditimpa dalam kelas turunan, mendapatkan nilai atribut dengan indeks yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | Saat ditimpa dalam kelas turunan, mendapatkan nilai atribut dengan indeks yang ditentukan. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Saat ditimpa dalam kelas turunan, mendapatkan nilai atribut dengan nilai [XmlReader::get_Name](./get_name/) yang ditentukan. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | Saat ditimpa dalam kelas turunan, mendapatkan nilai atribut dengan nilai [XmlReader::get_LocalName](./get_localname/) dan [XmlReader::get_NamespaceURI](./get_namespaceuri/) yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | Mengembalikan nilai yang menunjukkan apakah argumen string adalah nama XML yang valid. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | Mengembalikan nilai yang menunjukkan apakah argumen string adalah token nama XML yang valid. |
| virtual **bool** [IsStartElement](./isstartelement/)() | Memanggil [XmlReader::MoveToContent](./movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | Memanggil [XmlReader::MoveToContent](./movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_Name](./get_name/) dari elemen yang ditemukan cocok dengan argumen yang diberikan. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Memanggil [XmlReader::MoveToContent](./movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_LocalName](./get_localname/) dan [XmlReader::get_NamespaceURI](./get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | Saat ditimpa dalam kelas turunan, menyelesaikan prefiks namespace dalam ruang lingkup elemen saat ini. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | Saat ditimpa dalam kelas turunan, berpindah ke atribut dengan nilai [XmlReader::get_Name](./get_name/) yang ditentukan. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Saat ditimpa dalam kelas turunan, berpindah ke atribut dengan nilai [XmlReader::get_LocalName](./get_localname/) dan [XmlReader::get_NamespaceURI](./get_namespaceuri/) yang ditentukan. |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | Saat ditimpa dalam kelas turunan, berpindah ke atribut dengan indeks yang ditentukan. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | Memeriksa apakah node saat ini merupakan node konten (teks non-spasi, **CDATA**, **Element**, **EndElement**, **EntityReference**, atau **EndEntity**). Jika node bukan node konten, pembaca melompati ke node konten berikutnya atau akhir berkas. Ia melewatkan node dengan tipe berikut: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, atau **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | Saat ditimpa dalam kelas turunan, berpindah ke elemen yang berisi node atribut saat ini. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Saat ditimpa dalam kelas turunan, berpindah ke atribut pertama. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Saat ditimpa dalam kelas turunan, berpindah ke atribut berikutnya. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| virtual **bool** [Read](./read/)() | Saat ditimpa dalam kelas turunan, membaca node berikutnya dari stream. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | Saat ditimpa dalam kelas turunan, mengurai nilai atribut menjadi satu atau lebih node **[Text](../../system.text/)**, **EntityReference**, atau **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Membaca konten sebagai objek dari tipe yang ditentukan. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Membaca konten dan mengembalikan byte biner yang didekodekan Base64. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Membaca konten dan mengembalikan byte biner yang didekodekan **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | Membaca konten teks pada posisi saat ini sebagai [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | Membaca konten teks pada posisi saat ini sebagai objek [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Membaca konten teks pada posisi saat ini sebagai objek [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | Membaca konten teks pada posisi saat ini sebagai objek [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | Membaca konten teks pada posisi saat ini sebagai bilangan floating-point presisi ganda. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | Membaca konten teks pada posisi saat ini sebagai bilangan floating-point presisi tunggal. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | Membaca konten teks pada posisi saat ini sebagai bilangan bulat bertanda 32-bit. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | Membaca konten teks pada posisi saat ini sebagai bilangan bulat bertanda 64-bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | Membaca konten teks pada posisi saat ini sebagai [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | Membaca konten teks pada posisi saat ini sebagai objek [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Membaca konten elemen sebagai tipe yang diminta. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca konten elemen sebagai tipe yang diminta. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Membaca elemen dan mendekode konten **Base64**. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Membaca elemen dan mendekode konten **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai objek [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai objek [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai objek [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi ganda. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi ganda. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi tunggal. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi tunggal. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan bulat bertanda 32-bit. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai bilangan bulat bertanda 32-bit. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan bulat bertanda 64-bit. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai bilangan bulat bertanda 64-bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai objek [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | Membaca elemen hanya teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) sebagai gantinya, karena metode ini memberikan cara yang lebih langsung untuk menangani operasi ini. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | Memeriksa bahwa nilai [XmlReader::get_Name](./get_name/) dari elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen hanya teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) sebagai gantinya, karena metode ini memberikan cara yang lebih langsung untuk menangani operasi ini. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nilai [XmlReader::get_LocalName](./get_localname/) dan [XmlReader::get_NamespaceURI](./get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen hanya teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) sebagai gantinya, karena metode ini memberikan cara yang lebih langsung untuk menangani operasi ini. |
| virtual void [ReadEndElement](./readendelement/)() | Memeriksa bahwa node konten saat ini adalah tag penutup dan memajukan pembaca ke node berikutnya. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | Saat dioverride dalam kelas turunan, membaca semua konten, termasuk markup, sebagai string. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | Saat dioverride dalam kelas turunan, membaca konten, termasuk markup, yang mewakili node ini dan semua anaknya. |
| virtual void [ReadStartElement](./readstartelement/)() | Memeriksa bahwa node saat ini adalah elemen dan memajukan pembaca ke node berikutnya. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_Name](./get_name/) yang diberikan dan memajukan pembaca ke node berikutnya. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_LocalName](./get_localname/) dan [XmlReader::get_NamespaceURI](./get_namespaceuri/) yang diberikan dan memajukan pembaca ke node berikutnya. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Saat dioverride dalam kelas turunan, membaca isi elemen atau node teks sebagai string. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) sebagai gantinya, karena metode ini memberikan cara yang lebih langsung untuk menangani operasi ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | Mengembalikan instance [XmlReader](./) baru yang dapat digunakan untuk membaca node saat ini, dan semua turunannya. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | Majukan [XmlReader](./) ke elemen anak berikutnya dengan nama yang memenuhi syarat yang ditentukan. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Majukan [XmlReader](./) ke elemen anak berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | Membaca sampai elemen dengan nama yang memenuhi syarat yang ditentukan ditemukan. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Membaca sampai elemen dengan nama lokal dan URI namespace yang ditentukan ditemukan. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | Majukan [XmlReader](./) ke elemen saudara berikutnya dengan nama yang memenuhi syarat yang ditentukan. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Majukan [XmlReader](./) ke elemen saudara berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Membaca aliran teks besar yang disisipkan dalam dokumen XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan nilai tipe objek dengan nullptr berdasarkan referensi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| virtual void [ResolveEntity](./resolveentity/)() | Saat dioverride dalam kelas turunan, menyelesaikan referensi entitas untuk node **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [Skip](./skip/)() | Melewati anak-anak node saat ini. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() untuk membuka kunci. Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance kelas ini. |
## Lihat Juga

* Kelas [IDisposable](../../system/idisposable/)
* Ruang Nama [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)