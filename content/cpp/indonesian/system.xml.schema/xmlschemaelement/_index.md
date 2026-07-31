---
title: XmlSchemaElement
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili elemen element dari XML Schema sebagaimana ditentukan oleh World Wide Web Consortium (W3C). Kelas ini adalah kelas dasar untuk semua tipe partikel dan digunakan untuk mendeskripsikan sebuah elemen dalam dokumen XML.
type: docs
weight: 365
url: /id/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement kelas


Mewakili elemen **element** dari XML [Schema](../) sebagaimana ditentukan oleh World Wide [Web](../../system.web/) Consortium (W3C). Kelas ini adalah kelas dasar untuk semua tipe partikel dan digunakan untuk mendeskripsikan sebuah elemen dalam dokumen XML.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Mengembalikan properti **annotation**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Mengembalikan derivasi **Block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Mengembalikan interpretasi pasca-kompilasi dari nilai **Block**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | Mengembalikan koleksi kendala pada elemen. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Mengembalikan nilai default elemen jika isinya adalah tipe sederhana atau konten elemen adalah **textOnly**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | Mengembalikan objek [XmlSchemaType](../xmlschematype/) yang merepresentasikan tipe elemen berdasarkan nilai [XmlSchemaElement::get_SchemaType](./get_schematype/) atau [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) elemen. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | Mengembalikan objek berdasarkan [XmlSchemaElement](./) atau [XmlSchemaElement](./) elemen, yang menyimpan interpretasi pasca-kompilasi nilai **ElementType**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Mengembalikan nilai **Final** untuk menunjukkan bahwa tidak ada derivasi lebih lanjut yang diizinkan. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Mengembalikan interpretasi pasca-kompilasi nilai **Final**. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Mengembalikan nilai tetap. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Mengembalikan bentuk untuk elemen. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Mengembalikan id string. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Mengembalikan informasi yang menunjukkan apakah elemen dapat digunakan dalam dokumen instance. |
| **bool** [get_IsNillable](./get_isnillable/)() | Mengembalikan informasi yang menunjukkan apakah **xsi:nil** dapat muncul dalam data instance. Menunjukkan apakah nilai nil eksplisit dapat ditetapkan ke elemen. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Mengembalikan nomor baris dalam file yang dirujuk oleh elemen **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Mengembalikan posisi baris dalam file yang dirujuk oleh elemen **schema**. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Mengembalikan jumlah maksimum kemunculan partikel. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Mengembalikan jumlah sebagai nilai string. Jumlah maksimum kemunculan partikel. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Mengembalikan jumlah minimum kemunculan partikel. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Mengembalikan jumlah sebagai nilai string. Jumlah minimum kemunculan partikel. |
| [String](../../system/string/) [get_Name](./get_name/)() | Mengembalikan nama elemen. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Mengembalikan XmlSerializerNamespaces yang digunakan dengan objek skema ini. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Mengembalikan induk dari [XmlSchemaObject](../xmlschemaobject/) ini. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Mengembalikan nama terkualifikasi aktual untuk elemen yang diberikan. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Mengembalikan nama referensi elemen yang dideklarasikan dalam skema ini (atau skema lain yang ditunjukkan oleh namespace yang ditentukan). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | Mengembalikan tipe elemen. Ini dapat berupa tipe kompleks atau tipe sederhana. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Mengembalikan nama tipe data bawaan yang didefinisikan dalam skema ini atau skema lain yang ditunjukkan oleh namespace yang ditentukan. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Mengembalikan lokasi sumber untuk file yang memuat skema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | Mengembalikan nama elemen yang digantikan oleh elemen ini. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Mengembalikan atribut terkualifikasi yang tidak termasuk dalam namespace target skema saat ini. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merepresentasikan sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Mengatur properti **annotation**. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Mengatur derivasi **Block**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Mengatur nilai default elemen jika kontennya tipe sederhana atau konten elemen adalah **textOnly**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Mengatur nilai **Final** untuk menunjukkan tidak ada derivasi lebih lanjut yang diizinkan. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Mengatur nilai tetap. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Mengatur bentuk elemen. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Mengatur id string. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Mengatur informasi yang menunjukkan apakah elemen dapat digunakan dalam dokumen instance. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | Mengatur informasi yang menunjukkan apakah **xsi:nil** dapat muncul dalam data instance. Menunjukkan apakah nilai nil eksplisit dapat ditetapkan ke elemen. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Mengatur nomor baris dalam file yang dirujuk oleh elemen **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Mengatur posisi baris dalam file yang dirujuk oleh elemen **schema**. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Mengatur jumlah maksimum kemunculan partikel. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Mengatur jumlah sebagai nilai string. Jumlah maksimum kemunculan partikel. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Mengatur jumlah minimum kemunculan partikel. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Mengatur jumlah sebagai nilai string. Jumlah minimum kemunculan partikel. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Mengatur nama elemen. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Mengatur XmlSerializerNamespaces yang digunakan dengan objek skema ini. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Mengatur induk dari [XmlSchemaObject](../xmlschemaobject/) ini. |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Mengatur nama referensi elemen yang dideklarasikan dalam skema ini (atau skema lain yang ditunjukkan oleh namespace yang ditentukan). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Mengatur tipe elemen. Ini dapat berupa tipe kompleks atau tipe sederhana. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Mengatur nama tipe data bawaan yang didefinisikan dalam skema ini atau skema lain yang ditunjukkan oleh namespace yang ditentukan. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Mengatur lokasi sumber untuk file yang memuat skema. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Mengatur nama elemen yang digantikan oleh elemen ini. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Mengatur atribut terkualifikasi yang tidak termasuk dalam namespace target skema saat ini. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaiknya gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaiknya gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi weak. Tidak boleh dipanggil langsung; sebaiknya gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi weak. Tidak boleh dipanggil langsung; sebaiknya gunakan smart pointer atau ThisProtector. |
|  [XmlSchemaElement](./xmlschemaelement/)() | Menginisialisasi instance baru dari kelas [XmlSchemaElement](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Menginisialisasi instance baru dari kelas [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Menginisialisasi instance baru dari kelas [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Tipe alias

| Tipe alias | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance dari kelas ini. |

## Catatan



Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. 

## Lihat Juga

* Kelas [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Pustaka [Aspose.Slides](../../)