---
title: XmlTextReader
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili pembaca yang memberikan akses cepat, tidak ter-cache, hanya maju ke data XML.
type: docs
weight: 508
url: /id/system.xml/xmltextreader/
---
## XmlTextReader kelas

Mewakili pembaca yang menyediakan akses cepat, tidak ter-cache, hanya maju ke data XML.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Metode

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Mengubah [XmlReader::get_ReadState](../xmlreader/get_readstate/) menjadi **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan URI yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan URI dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan URI, pengaturan, dan informasi konteks untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru menggunakan aliran yang ditentukan dengan pengaturan default. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan aliran dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Membuat instance [XmlReader](../xmlreader/) baru menggunakan aliran yang ditentukan, URI dasar, dan pengaturan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru menggunakan aliran yang ditentukan, pengaturan, dan informasi konteks untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks dan pengaturan yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks, pengaturan, dan URI dasar yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca teks, pengaturan, dan informasi konteks untuk parsing. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Membuat instance [XmlReader](../xmlreader/) baru dengan menggunakan pembaca XML dan pengaturan yang ditentukan. |
| void [Dispose](../xmlreader/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh instance kelas [XmlReader](../xmlreader/) saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Mengembalikan jumlah atribut pada node saat ini. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Mengembalikan URI dasar dari node saat ini. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Mengembalikan nilai yang menunjukkan apakah [XmlTextReader](./) mengimplementasikan metode pembacaan konten biner. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Mengembalikan nilai yang menunjukkan apakah [XmlTextReader](./) mengimplementasikan metode [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Mengembalikan nilai yang menunjukkan apakah pembaca ini dapat mengurai dan menyelesaikan entitas. |
| **int32_t** [get_Depth](./get_depth/)() override | Mengembalikan kedalaman node saat ini dalam dokumen XML. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Mengembalikan enumerasi DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Mengembalikan enkoding dokumen. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Mengembalikan nilai yang menentukan bagaimana pembaca menangani entitas. |
| **bool** [get_EOF](./get_eof/)() override | Mengembalikan nilai yang menunjukkan apakah pembaca berada pada akhir aliran. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Mengembalikan nilai yang menunjukkan apakah node saat ini memiliki atribut. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini dapat memiliki [XmlTextReader::get_Value](./get_value/) selain [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini adalah atribut yang dihasilkan dari nilai default yang didefinisikan dalam DTD atau skema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini adalah elemen kosong (misalnya, **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Mengembalikan nomor baris saat ini. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Mengembalikan posisi baris saat ini. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Mengembalikan nama lokal node saat ini. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Mengembalikan nama lengkap node saat ini. |
| **bool** [get_Namespaces](./get_namespaces/)() | Mengembalikan nilai yang menunjukkan apakah mendukung namespace. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Mengembalikan URI namespace (seperti yang didefinisikan dalam spesifikasi Namespace W3C) dari node tempat pembaca berada. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Mengembalikan [XmlNameTable](../xmlnametable/) yang terkait dengan implementasi ini. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Mengembalikan tipe node saat ini. |
| **bool** [get_Normalization](./get_normalization/)() | Mengembalikan nilai yang menunjukkan apakah harus menormalkan spasi putih dan nilai atribut. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Mengembalikan prefiks namespace yang terkait dengan node saat ini. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Mengembalikan nilai yang menunjukkan apakah mengizinkan pemrosesan DTD. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Mengembalikan karakter tanda kutip yang digunakan untuk mengurung nilai atribut node. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Mengembalikan status pembaca. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Mengembalikan informasi skema yang telah diberikan ke node saat ini sebagai hasil validasi skema. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Mengembalikan objek [XmlReaderSettings](../xmlreadersettings/) yang digunakan untuk membuat instance [XmlReader](../xmlreader/) ini. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Mengembalikan nilai teks node saat ini. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Mengembalikan tipe untuk node saat ini. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Mengembalikan nilai yang menentukan bagaimana spasi putih ditangani. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Mengembalikan ruang lingkup **xml:lang** saat ini. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Mengembalikan ruang lingkup **xml:space** saat ini. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Mengembalikan nilai atribut dengan nama yang ditentukan. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Mengembalikan nilai atribut dengan nama lokal dan URI namespace yang ditentukan. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Mengembalikan nilai atribut dengan indeks yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Mengembalikan koleksi yang berisi semua namespace yang saat ini dalam ruang lingkup. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Mengembalikan sisa XML yang di-buffer. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Mengembalikan nilai yang menunjukkan apakah kelas dapat mengembalikan informasi baris. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Saat dioverride dalam kelas turunan, mendapatkan nilai atribut dengan indeks yang ditentukan. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Saat dioverride dalam kelas turunan, mendapatkan nilai atribut dengan nilai [XmlReader::get_Name](../xmlreader/get_name/) yang ditentukan. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Saat dioverride dalam kelas turunan, mendapatkan nilai atribut dengan nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Mengembalikan nilai yang menunjukkan apakah argumen string adalah nama XML yang valid. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Mengembalikan nilai yang menunjukkan apakah argumen string merupakan token nama XML yang valid. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_Name](../xmlreader/get_name/) dari elemen yang ditemukan cocok dengan argumen yang diberikan. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Memanggil [XmlReader::MoveToContent](../xmlreader/movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Menyelesaikan prefiks namespace dalam ruang lingkup elemen saat ini. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Berpindah ke atribut dengan nama yang ditentukan. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Berpindah ke atribut dengan nama lokal dan URI namespace yang ditentukan. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Berpindah ke atribut dengan indeks yang ditentukan. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Memeriksa apakah node saat ini adalah node konten (teks non-spasi putih, **CDATA**, **Element**, **EndElement**, **EntityReference**, atau **EndEntity**). Jika node bukan node konten, pembaca melompati ke node konten berikutnya atau akhir file. Ia melewatkan node dengan tipe berikut: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, atau **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Berpindah ke elemen yang berisi node atribut saat ini. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Berpindah ke atribut pertama. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Berpindah ke atribut berikutnya. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| **bool** [Read](./read/)() override | Membaca node berikutnya dari aliran. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Menganalisis nilai atribut menjadi satu atau lebih node **[Text](../../system.text/)**, **EntityReference**, atau **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mendekode Base64 dan mengembalikan byte biner yang terdekripsi. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mendekode **BinHex** dan mengembalikan byte biner yang terdekripsi. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Membaca isi teks dari sebuah elemen ke dalam buffer karakter. Metode ini dirancang untuk membaca aliran teks tersemat yang besar dengan memanggilnya secara berurutan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Membaca isi sebagai objek dari tipe yang ditentukan. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca isi dan mengembalikan byte biner hasil dekode **Base64**. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca isi dan mengembalikan byte biner hasil dekode **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Membaca isi teks pada posisi saat ini sebagai [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Membaca isi teks pada posisi saat ini sebagai objek [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Membaca isi teks pada posisi saat ini sebagai objek [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Membaca isi teks pada posisi saat ini sebagai objek [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Membaca isi teks pada posisi saat ini sebagai bilangan floating-point presisi ganda. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Membaca isi teks pada posisi saat ini sebagai bilangan floating-point presisi tunggal. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Membaca isi teks pada posisi saat ini sebagai bilangan bulat bertanda 32-bit. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Membaca isi teks pada posisi saat ini sebagai bilangan bulat bertanda 64-bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Membaca isi teks pada posisi saat ini sebagai [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Membaca isi teks pada posisi saat ini sebagai objek [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Membaca isi elemen sebagai tipe yang diminta. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca isi elemen sebagai tipe yang diminta. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca elemen dan mendekode konten Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Membaca elemen dan mendekode konten **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai objek [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai objek [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai objek [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi ganda. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi ganda. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi tunggal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai bilangan floating-point presisi tunggal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan bulat bertanda 32-bit. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai bilangan bulat bertanda 32-bit. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai bilangan bulat bertanda 64-bit. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai bilangan bulat bertanda 64-bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Membaca elemen saat ini dan mengembalikan isinya sebagai objek [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nama lokal dan URI namespace yang ditentukan sesuai dengan elemen saat ini, lalu membaca elemen saat ini dan mengembalikan isinya sebagai objek [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) sebagai gantinya, karena metode tersebut menyediakan cara yang lebih sederhana untuk menangani operasi ini. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Memeriksa bahwa nilai [XmlReader::get_Name](../xmlreader/get_name/) dari elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) sebagai gantinya, karena metode tersebut menyediakan cara yang lebih sederhana untuk menangani operasi ini. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) sebagai gantinya, karena metode tersebut menyediakan cara yang lebih sederhana untuk menangani operasi ini. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Memeriksa bahwa node konten saat ini adalah tag penutup dan memajukan pembaca ke node berikutnya. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Saat dioverride dalam kelas turunan, membaca seluruh konten, termasuk markup, sebagai string. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Saat dioverride dalam kelas turunan, membaca konten, termasuk markup, yang mewakili node ini dan semua anaknya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Memeriksa bahwa node saat ini adalah elemen dan memajukan pembaca ke node berikutnya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_Name](../xmlreader/get_name/) yang diberikan dan memajukan pembaca ke node berikutnya. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_LocalName](../xmlreader/get_localname/) dan [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) yang diberikan dan memajukan pembaca ke node berikutnya. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Membaca isi sebuah elemen atau node teks sebagai string. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Mengembalikan instance [XmlReader](../xmlreader/) baru yang dapat digunakan untuk membaca node saat ini, dan semua turunannya. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Memajukan [XmlReader](../xmlreader/) ke elemen keturunan berikutnya dengan nama terkuantifikasi yang ditentukan. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Memajukan [XmlReader](../xmlreader/) ke elemen keturunan berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Membaca hingga menemukan elemen dengan nama terkuantifikasi yang ditentukan. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Membaca hingga menemukan elemen dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Memajukan [XmlReader](../xmlreader/) ke elemen saudara berikutnya dengan nama terkuantifikasi yang ditentukan. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Memajukan [XmlReader](../xmlreader/) ke elemen saudara berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Membaca aliran teks besar yang tersemat dalam dokumen XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [ResetState](./resetstate/)() | Mengatur ulang keadaan pembaca ke [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Menyelesaikan referensi entitas untuk node **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Mengatur enumerasi DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Mengatur nilai yang menentukan bagaimana pembaca menangani entitas. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Mengatur nilai yang menunjukkan apakah mendukung namespace. |
| void [set_Normalization](./set_normalization/)(**bool**) | Mengatur nilai yang menunjukkan apakah menormalkan spasi putih dan nilai atribut. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Mengatur nilai yang menunjukkan apakah mengizinkan pemrosesan DTD. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Mengatur nilai yang menentukan bagaimana spasi putih ditangani. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Mengatur [XmlResolver](../xmlresolver/) yang digunakan untuk menyelesaikan referensi DTD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector sebagai gantinya. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector sebagai gantinya. |
| void [Skip](./skip/)() override | Melewati anak-anak node saat ini. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembebasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan weak reference. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector sebagai gantinya. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan weak reference. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector sebagai gantinya. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Menginisialisasi instance baru dari kelas [XmlTextReader](./) dengan stream yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Menginisialisasi instance baru dari kelas [XmlTextReader](./) dengan URL dan stream yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Menginisialisasi instance baru dari kelas [XmlTextReader](./) dengan stream dan [XmlNameTable](../xmlnametable/) yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Menginisialisasi instance baru dari kelas [XmlTextReader](./) dengan URL, stream, dan [XmlNameTable](../xmlnametable/) yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Menginisialisasi sebuah instance baru dari kelas [XmlTextReader](./) dengan TextReader yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Menginisialisasi sebuah instance baru dari kelas [XmlTextReader](./) dengan URL dan TextReader yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Menginisialisasi sebuah instance baru dari kelas [XmlTextReader](./) dengan TextReader dan [XmlNameTable](../xmlnametable/) yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Menginisialisasi sebuah instance baru dari kelas [XmlTextReader](./) dengan URL, TextReader, dan [XmlNameTable](../xmlnametable/) yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Menginisialisasi sebuah instance baru dari kelas [XmlTextReader](./) dengan stream, XmlNodeType, dan [XmlParserContext](../xmlparsercontext/) yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Menginisialisasi sebuah instance baru dari kelas [XmlTextReader](./) dengan string, XmlNodeType, dan [XmlParserContext](../xmlparsercontext/) yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Menginisialisasi sebuah instance baru dari kelas [XmlTextReader](./) dengan file yang ditentukan. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Menginisialisasi sebuah instance baru dari kelas [XmlTextReader](./) dengan file dan [XmlNameTable](../xmlnametable/) yang ditentukan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance kelas ini. |
## Keterangan



Disarankan untuk menggunakan kelas [XmlReader](../xmlreader/) sebagai gantinya. 

Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk mengirimkannya ke fungsi sebagai argumen. 

## Lihat Juga

* Kelas [XmlReader](../xmlreader/)
* Kelas [IXmlLineInfo](../ixmllineinfo/)
* Kelas [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)