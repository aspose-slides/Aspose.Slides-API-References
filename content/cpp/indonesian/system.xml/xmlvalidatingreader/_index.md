---
title: XmlValidatingReader
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili pembaca yang menyediakan validasi definisi tipe dokumen (DTD), skema XML-Data Reduced (XDR), dan bahasa definisi XML Schema (XSD).
type: docs
weight: 547
url: /id/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader kelas

Mewakili pembaca yang menyediakan definisi tipe dokumen (DTD), skema XML-Data Reduced (XDR), dan bahasa definisi XML [Schema](../../system.xml.schema/) (XSD) untuk validasi.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Close](./close/)() override | Mengubah [XmlReader::get_ReadState](../xmlreader/get_readstate/) menjadi Closed. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan URI yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan URI dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan URI, pengaturan, dan informasi konteks yang ditentukan untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru menggunakan stream yang ditentukan dengan pengaturan default. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan stream dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Membuat instance [XmlReader](../xmlreader/) baru menggunakan stream yang ditentukan, URI dasar, dan pengaturan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru menggunakan stream, pengaturan, dan informasi konteks yang ditentukan untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks, pengaturan, dan URI dasar yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks, pengaturan, dan informasi konteks yang ditentukan untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca XML dan pengaturan yang ditentukan. |
| void [Dispose](../xmlreader/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh instance kelas [XmlReader](../xmlreader/) saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Mengembalikan jumlah atribut pada node saat ini. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Mengembalikan URI dasar node saat ini. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Mengembalikan nilai yang menunjukkan apakah [XmlValidatingReader](./) mengimplementasikan metode membaca konten biner. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Mengembalikan nilai yang menunjukkan apakah [XmlReader](../xmlreader/) mengimplementasikan metode [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Mengembalikan nilai yang menunjukkan apakah pembaca ini dapat mengurai dan menyelesaikan entitas. |
| **int32_t** [get_Depth](./get_depth/)() override | Mengembalikan kedalaman node saat ini dalam dokumen XML. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Mengembalikan atribut encoding untuk dokumen. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Mengembalikan nilai yang menentukan bagaimana pembaca menangani entitas. |
| **bool** [get_EOF](./get_eof/)() override | Mengembalikan nilai yang menunjukkan apakah pembaca berada pada akhir stream. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Mengembalikan nilai yang menunjukkan apakah node saat ini memiliki atribut. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini dapat memiliki [XmlValidatingReader::get_Value](./get_value/) selain [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini adalah atribut yang dihasilkan dari nilai default yang didefinisikan dalam definisi tipe dokumen (DTD) atau skema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini adalah elemen kosong (misalnya, **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Mengembalikan nomor baris saat ini. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Mengembalikan posisi baris saat ini. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Mengembalikan nama lokal node saat ini. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Mengembalikan nama lengkap node saat ini. |
| **bool** [get_Namespaces](./get_namespaces/)() | Mengembalikan nilai yang menunjukkan apakah mendukung namespace. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Mengembalikan Uniform Resource Identifier (URI) namespace (sebagaimana didefinisikan dalam konsorsium World Wide [Web](../../system.web/) (W3C) spesifikasi Namespace) dari node tempat pembaca berada. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Mengembalikan [XmlNameTable](../xmlnametable/) yang terkait dengan implementasi ini. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Mengembalikan tipe node saat ini. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Mengembalikan awalan namespace yang terkait dengan node saat ini. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Mengembalikan karakter tanda kutip yang digunakan untuk mengelilingi nilai dari node atribut. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Mengembalikan [XmlReader](../xmlreader/) yang digunakan untuk membangun [XmlValidatingReader](./) ini. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Mengembalikan status pembaca. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Mengembalikan informasi skema yang telah ditetapkan ke node saat ini sebagai hasil validasi skema. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Mengembalikan XmlSchemaCollection untuk digunakan dalam validasi. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Mengembalikan objek tipe skema. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Mengembalikan objek [XmlReaderSettings](../xmlreadersettings/) yang digunakan untuk membuat instance [XmlReader](../xmlreader/) ini. |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Mengembalikan nilai yang menunjukkan tipe validasi yang akan dilakukan. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Mengembalikan nilai teks dari node saat ini. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Mengembalikan tipe untuk node saat ini. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Mengembalikan ruang lingkup **xml:lang** saat ini. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Mengembalikan ruang lingkup **xml:space** saat ini. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Mengembalikan nilai atribut dengan nama yang ditentukan. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Mengembalikan nilai atribut dengan nama lokal dan URI namespace yang ditentukan. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Mengembalikan nilai atribut dengan indeks yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Mengembalikan nilai yang menunjukkan apakah kelas dapat mengembalikan informasi baris. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Saat dioverride dalam kelas turunan, mendapatkan nilai atribut dengan indeks yang ditentukan. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Saat dioverride dalam kelas turunan, mendapatkan nilai atribut dengan nilai [XmlReader::get_Name](../xmlreader/get_name/) yang ditentukan. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Saat dioverride dalam kelas turunan, mendapatkan nilai atribut dengan nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Mengembalikan nilai yang menunjukkan apakah argumen string adalah nama XML yang valid. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Mengembalikan nilai yang menunjukkan apakah argumen string adalah token nama XML yang valid. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_Name](../xmlreader/get_name/) dari elemen yang ditemukan cocok dengan argumen yang diberikan. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Menyelesaikan awalan namespace dalam ruang lingkup elemen saat ini. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Berpindah ke atribut dengan nama yang ditentukan. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Berpindah ke atribut dengan nama lokal dan URI namespace yang ditentukan. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Berpindah ke atribut dengan indeks yang ditentukan. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Memeriksa apakah node saat ini adalah node konten (teks bukan spasi, **CDATA**, **Element**, **EndElement**, **EntityReference**, atau **EndEntity**). Jika node bukan node konten, pembaca melewati ke node konten berikutnya atau akhir file. Ia melewati node dengan tipe berikut: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, atau **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Berpindah ke elemen yang berisi node atribut saat ini. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Berpindah ke atribut pertama. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Berpindah ke atribut berikutnya. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| **bool** [Read](./read/)() override | Membaca node berikutnya dari stream. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Mengurai nilai atribut menjadi satu atau lebih node **[Text](../../system.text/)**, **EntityReference**, atau **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Membaca konten sebagai objek dengan tipe yang ditentukan. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca konten dan mengembalikan byte biner hasil decode Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca konten dan mengembalikan byte biner hasil decode BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Membaca konten teks pada posisi saat ini sebagai [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Membaca konten teks pada posisi saat ini sebagai objek [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Membaca konten teks pada posisi saat ini sebagai objek [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Membaca konten teks pada posisi saat ini sebagai objek [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Membaca konten teks pada posisi saat ini sebagai angka floating-point double-precision. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Membaca konten teks pada posisi saat ini sebagai angka floating-point single-precision. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Membaca konten teks pada posisi saat ini sebagai integer bertanda 32-bit. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Membaca konten teks pada posisi saat ini sebagai integer bertanda 64-bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Membaca konten teks pada posisi saat ini sebagai [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Membaca konten teks pada posisi saat ini sebagai objek [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Membaca konten elemen sebagai tipe yang diminta. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca konten elemen sebagai tipe yang diminta. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca elemen dan mendekode konten Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca elemen dan mendekode konten BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai objek [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai objek [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai objek [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai angka floating-point double-precision. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai angka floating-point double-precision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai angka floating-point single-precision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai angka floating-point single-precision. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai integer bertanda 32-bit. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai integer bertanda 32-bit. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai integer bertanda 64-bit. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai integer bertanda 64-bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai objek [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) karena menyediakan cara yang lebih langsung untuk menangani operasi ini. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Memeriksa bahwa nilai [XmlReader::get_Name](../xmlreader/get_name/) elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) karena menyediakan cara yang lebih langsung untuk menangani operasi ini. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) karena menyediakan cara yang lebih langsung untuk menangani operasi ini. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Memeriksa bahwa node konten saat ini adalah tag akhir dan memajukan pembaca ke node berikutnya. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Ketika dioverride di kelas turunan, membaca semua konten, termasuk markup, sebagai string. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Ketika dioverride di kelas turunan, membaca konten, termasuk markup, yang merepresentasikan node ini dan semua anaknya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Memeriksa bahwa node saat ini adalah elemen dan memajukan pembaca ke node berikutnya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_Name](../xmlreader/get_name/) yang diberikan dan memajukan pembaca ke node berikutnya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) yang diberikan dan memajukan pembaca ke node berikutnya. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Membaca isi elemen atau node teks sebagai string. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Mengembalikan instance [XmlReader](../xmlreader/) baru yang dapat digunakan untuk membaca node saat ini, dan semua descendant-nya. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Memajukan [XmlReader](../xmlreader/) ke elemen descendant berikutnya dengan nama terqualifikasi yang ditentukan. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Memajukan [XmlReader](../xmlreader/) ke elemen descendant berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Membaca sampai elemen dengan nama terqualifikasi yang ditentukan ditemukan. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Membaca sampai elemen dengan nama lokal dan URI namespace yang ditentukan ditemukan. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Memajukan [XmlReader](../xmlreader/) ke elemen saudara berikutnya dengan nama terqualifikasi yang ditentukan. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Memajukan [XmlReader](../xmlreader/) ke elemen saudara berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Mengembalikan tipe runtime untuk bahasa definisi XML [Schema](../../system.xml.schema/) (XSD) yang ditentukan. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Membaca aliran teks besar yang disisipkan dalam dokumen XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan nilai tipe objek dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitung referensi bersama sebesar nilai yang ditentukan. |
| void [ResolveEntity](./resolveentity/)() override | Menyelesaikan referensi entitas untuk node **EntityReference**. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Menetapkan nilai yang menentukan cara pembaca menangani entitas. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Menetapkan nilai yang menunjukkan apakah dukungan namespace diaktifkan. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Menetapkan nilai yang menunjukkan jenis validasi yang akan dilakukan. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Menetapkan [XmlResolver](../xmlresolver/) yang digunakan untuk menyelesaikan referensi definisi tipe dokumen eksternal (DTD) dan skema lokasi. [XmlResolver](../xmlresolver/) juga digunakan untuk menangani elemen import atau include yang ditemukan dalam skema bahasa definisi XML [Schema](../../system.xml.schema/) (XSD). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n sebagai weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | Melewatkan anak dari node saat ini. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() yang membuka kunci. Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Menambahkan penangan peristiwa untuk menerima informasi tentang kesalahan validasi DTD, skema XML-Data Reduced (XDR), dan skema bahasa definisi XML [Schema](../../system.xml.schema/) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Menghapus penangan peristiwa untuk menerima informasi tentang kesalahan validasi DTD, skema XML-Data Reduced (XDR), dan skema bahasa definisi XML [Schema](../../system.xml.schema/) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | Menginisialisasi instance baru kelas [XmlValidatingReader](./) yang memvalidasi konten yang dikembalikan dari [XmlReader](../xmlreader/) yang diberikan. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Menginisialisasi instance baru kelas [XmlValidatingReader](./) dengan nilai-nilai yang ditentukan. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Menginisialisasi instance baru kelas [XmlValidatingReader](./) dengan nilai-nilai yang ditentukan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance kelas ini. |
## Keterangan

Usang
:   Kelas ini sudah usang. Disarankan untuk menggunakan kelas [XmlReaderSettings](../xmlreadersettings/) dan metode [XmlReader::Create](../xmlreader/create/) untuk membuat pembaca XML yang memvalidasi.
Objek dari kelas ini harus hanya dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance dari tipe ini pada stack atau dengan menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. 

## Lihat Juga

* Kelas [XmlReader](../xmlreader/)
* Kelas [IXmlLineInfo](../ixmllineinfo/)
* Kelas [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Ruang Nama [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)