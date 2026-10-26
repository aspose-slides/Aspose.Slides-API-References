---
title: XmlNodeReader
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili pembaca yang menyediakan akses cepat, tidak ter-cache, hanya maju ke data XML dalam sebuah XmlNode.
type: docs
weight: 365
url: /id/system.xml/xmlnodereader/
---
## XmlNodeReader kelas


Mewakili pembaca yang menyediakan akses maju cepat, tidak ter-cache, hanya ke data XML dalam sebuah [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Metode

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Mengubah [XmlNodeReader::get_ReadState](./get_readstate/) menjadi [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan URI yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan menggunakan URI dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan menggunakan URI, pengaturan, dan informasi konteks yang ditentukan untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru menggunakan stream yang ditentukan dengan pengaturan default. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan stream dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru menggunakan stream, URI dasar, dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru menggunakan stream, pengaturan, dan informasi konteks untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks, pengaturan, dan URI dasar yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks, pengaturan, dan informasi konteks untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Membuat sebuah instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca XML dan pengaturan yang ditentukan. |
| void [Dispose](../xmlreader/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh instance [XmlReader](../xmlreader/) kelas saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Mengembalikan jumlah atribut pada node saat ini. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Mengembalikan URI dasar dari node saat ini. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Mengembalikan nilai yang menunjukkan apakah [XmlNodeReader](./) mengimplementasikan metode pembacaan konten biner. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Mengembalikan nilai yang menunjukkan apakah [XmlReader](../xmlreader/) mengimplementasikan metode [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Mengembalikan nilai yang menunjukkan apakah pembaca ini dapat mengurai dan menyelesaikan entitas. |
| **int32_t** [get_Depth](./get_depth/)() override | Mengembalikan kedalaman node saat ini dalam dokumen XML. |
| **bool** [get_EOF](./get_eof/)() override | Mengembalikan nilai yang menunjukkan apakah pembaca berada pada akhir stream. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini memiliki atribut. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini dapat memiliki nilai [XmlNodeReader::get_Value](./get_value/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini adalah atribut yang dihasilkan dari nilai default yang didefinisikan dalam definisi tipe dokumen (DTD) atau skema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini adalah elemen kosong (misalnya, **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Mengembalikan nama lokal dari node saat ini. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Mengembalikan nama lengkap (qualified) dari node saat ini. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Mengembalikan URI namespace (seperti yang didefinisikan dalam spesifikasi Namespace W3C) dari node tempat pembaca berada. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Mengembalikan [XmlNameTable](../xmlnametable/) yang terkait dengan implementasi ini. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Mengembalikan tipe dari node saat ini. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Mengembalikan prefiks namespace yang terkait dengan node saat ini. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Saat dioverride dalam kelas turunan, mengambil karakter tanda kutip yang digunakan untuk mengurung nilai node atribut. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Mengembalikan status pembaca. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Mengembalikan informasi skema yang telah ditetapkan ke node saat ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Mengembalikan objek [XmlReaderSettings](../xmlreadersettings/) yang digunakan untuk membuat instance [XmlReader](../xmlreader/) ini. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Mengembalikan nilai teks dari node saat ini. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Mengembalikan tipe untuk node saat ini. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Mengembalikan ruang lingkup **xml:lang** saat ini. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Mengembalikan ruang lingkup **xml:space** saat ini. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Mengembalikan nilai atribut dengan nama yang ditentukan. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Mengembalikan nilai atribut dengan nama lokal dan URI namespace yang ditentukan. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Mengembalikan nilai atribut dengan indeks yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan indeks yang ditentukan. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan nilai [XmlReader::get_Name](../xmlreader/get_name/) yang ditentukan. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Saat dioverride dalam kelas turunan, mengambil nilai atribut dengan nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Mengembalikan nilai yang menunjukkan apakah argumen string adalah nama XML yang valid. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Mengembalikan nilai yang menunjukkan apakah argumen string adalah token nama XML yang valid. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_Name](../xmlreader/get_name/) dari elemen yang ditemukan cocok dengan argumen yang diberikan. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Menyelesaikan prefiks namespace dalam ruang lingkup elemen saat ini. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Berpindah ke atribut dengan nama yang ditentukan. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Berpindah ke atribut dengan nama lokal dan URI namespace yang ditentukan. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Berpindah ke atribut dengan indeks yang ditentukan. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Memeriksa apakah node saat ini adalah node konten (teks bukan spasi putih, **CDATA**, **Element**, **EndElement**, **EntityReference**, atau **EndEntity**). Jika node bukan node konten, pembaca melompati ke node konten berikutnya atau akhir file. Ia melewati node dengan tipe berikut: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, atau **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Berpindah ke elemen yang berisi node atribut saat ini. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Berpindah ke atribut pertama. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Berpindah ke atribut berikutnya. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| **bool** [Read](./read/)() override | Membaca node berikutnya dari stream. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Menganalisis nilai atribut menjadi satu atau lebih node **[Text](../../system.text/)**, **EntityReference**, atau **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Membaca konten sebagai objek dengan tipe yang ditentukan. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca konten dan mengembalikan byte biner yang didekodekan Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca konten dan mengembalikan byte biner yang didekodekan BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Membaca konten teks pada posisi saat ini sebagai [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Membaca konten teks pada posisi saat ini sebagai objek [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Membaca konten teks pada posisi saat ini sebagai objek [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Membaca konten teks pada posisi saat ini sebagai objek [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Membaca konten teks pada posisi saat ini sebagai angka floating-point double presisi. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Membaca konten teks pada posisi saat ini sebagai angka floating-point presisi tunggal. |
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
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point double presisi. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point double presisi. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi tunggal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi tunggal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai integer bertanda 32-bit. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai integer bertanda 32-bit. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai integer bertanda 64-bit. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai integer bertanda 64-bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen saat ini dan mengembalikan isinya sebagai objek [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Membaca elemen hanya teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) sebagai gantinya, karena memberikan cara yang lebih sederhana untuk menangani operasi ini. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Memeriksa bahwa nilai [XmlReader::get_Name](../xmlreader/get_name/) dari elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen hanya teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) sebagai gantinya, karena memberikan cara yang lebih sederhana untuk menangani operasi ini. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen hanya teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) sebagai gantinya, karena memberikan cara yang lebih sederhana untuk menangani operasi ini. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Memeriksa bahwa node konten saat ini adalah tag penutup dan melanjutkan pembaca ke node berikutnya. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Ketika dioverride dalam kelas turunan, membaca semua konten, termasuk markup, sebagai string. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Ketika dioverride dalam kelas turunan, membaca konten, termasuk markup, yang mewakili node ini dan semua anaknya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Memeriksa bahwa node saat ini adalah elemen dan melanjutkan pembaca ke node berikutnya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_Name](../xmlreader/get_name/) yang diberikan dan melanjutkan pembaca ke node berikutnya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) yang diberikan dan melanjutkan pembaca ke node berikutnya. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Membaca isi elemen atau node teks sebagai string. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Mengembalikan instance [XmlReader](../xmlreader/) baru yang dapat digunakan untuk membaca node saat ini, dan semua keturunannya. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Meneruskan [XmlReader](../xmlreader/) ke elemen keturunan berikutnya dengan nama terkwalifikasi yang ditentukan. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Meneruskan [XmlReader](../xmlreader/) ke elemen keturunan berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Membaca sampai elemen dengan nama terkwalifikasi yang ditentukan ditemukan. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Membaca sampai elemen dengan nama lokal dan URI namespace yang ditentukan ditemukan. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Meneruskan [XmlReader](../xmlreader/) ke elemen saudara berikutnya dengan nama terkwalifikasi yang ditentukan. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Meneruskan [XmlReader](../xmlreader/) ke elemen saudara berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Membaca aliran teks besar yang tertanam dalam dokumen XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek secara referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek secara referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [ResolveEntity](./resolveentity/)() override | Menyelesaikan referensi entitas untuk **EntityReference** nodes. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [Skip](./skip/)() override | Melewati anak node saat ini. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi weak. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi weak. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Membuat instance kelas [XmlNodeReader](./) menggunakan [XmlNode](../xmlnode/) yang ditentukan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk pointer bersama ke suatu instance kelas ini. |

## Remarks

Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen. 

## See Also

* Kelas [XmlReader](../xmlreader/)
* Kelas [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Ruang Nama [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)